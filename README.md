# SEP

### **Affordable Housing and Tenant Finder**

---

### **Aim:**  
To design and develop an efficient and user-friendly platform that connects tenants with landlords for affordable housing. The system should address issues of trust, transparency, and accessibility in the housing rental process, particularly targeting students, working professionals, and low-income groups.

---

### **Problem Statement:**  
The rental housing market in India faces significant challenges, including:  
1. **Lack of Transparency:** Tenants struggle to find verified properties, and landlords face issues finding trustworthy tenants.  
2. **Inefficient Communication:** Traditional methods of communication between landlords and tenants are time-consuming.  
3. **Accessibility Issues:** Many users, especially in lower-income groups, lack access to reliable platforms to find affordable housing.  
4. **Roommate Matching:** Shared housing solutions are often disorganized and lack compatibility checks.  
5. **Payment and Documentation:** Managing rental payments and agreements manually is cumbersome and error-prone.

**Proposed Solution:**  
Develop a platform where:  
- Landlords can list their properties with verified details.  
- Tenants can find housing using advanced search filters.  
- Automated features like roommate matching, rental agreements, and secure online payments simplify the process.  

---

### **Model Used: Agile Process Model**  

**Reason for Selection:**  
1. The **Agile Process Model** is iterative, making it suitable for incorporating user feedback during development.  
2. Housing needs and user preferences may vary, requiring frequent updates and refinements.  
3. Agile ensures quick delivery of an MVP (Minimum Viable Product) while enabling the addition of advanced features later.

---


# Software Requirements Specification (SRS)

## 1. Introduction

### 1.1 Purpose
The purpose of this system is to streamline the housing rental process by creating a platform where landlords and tenants can connect, ensuring transparency, ease of use, and accessibility.
- Provide a secure and reliable platform for rental transactions.
- Facilitate better communication between landlords and tenants.

### 1.2 Document Conventions
- Text in **bold** represents section headings.
- Text in *italic* represents important terms or emphasis.
- Code snippets and technical terms will be highlighted in `monospace font`.
- Numbered lists indicate sequential steps or processes.

### 1.3 Intended Audience and Reading Suggestions
This document is intended for developers, project managers, and stakeholders involved in the development and implementation of the housing rental platform. Readers are advised to start with the Introduction for an overview and then move to the Overall Description and System Features for detailed requirements.
- Developers: Focus on sections 2 and 3 for detailed technical requirements.
- Project Managers: Review the entire document to understand the project scope and requirements.
- Stakeholders: Read sections 1 and 2 for a high-level overview.

### 1.4 Project Scope
The platform will:
- Enable landlords to list properties with detailed information.
- Provide tenants with tools to search for affordable housing.
- Support roommate matching and secure online rental payments.
- Generate digital rental agreements.
- Include features for user feedback and ratings.
- Offer customer support and dispute resolution mechanisms.

### 1.5 References
- Government housing policies.
- Market research reports on the rental housing sector in India.
- Documentation for third-party APIs used (e.g., Google Maps, Razorpay).
- User feedback from similar platforms.

## 2. Overall Description

### 2.1 Product Perspective
The platform will be a web and mobile application with intuitive UI/UX design. It will be integrated with third-party APIs like Google Maps for location-based services and payment gateways for online transactions.
- The system will be modular, allowing for future enhancements and scalability.
- The platform will support both English and regional languages.

### 2.2 Product Features
- Property listing and search with filters.
- Verified user profiles (landlords and tenants).
- Rent payment and roommate matching.
- Push notifications for updates (e.g., new listings or payment reminders).
- User feedback and rating system for properties and users.
- In-app messaging for communication between landlords and tenants.

### 2.3 User Classes and Characteristics
- **Landlords**: List properties, verify ownership, and manage tenants.
  - Receive notifications for tenant inquiries and payments.
  - Access analytics on property views and interests.
- **Tenants**: Search for properties, negotiate rents, and pay online.
  - Save favorite properties and receive alerts for new listings.
  - Use the platform for lease management and maintenance requests.
- **Admin**: Oversee operations, manage user verification, and handle disputes.
  - Monitor platform usage and generate reports.
  - Manage system settings and configurations.

### 2.4 Operating Environment
- **Mobile Application**: Android and iOS.
  - Compatible with devices running Android 5.0+ and iOS 10.0+.
- **Web Application**: Compatible with modern browsers.
  - Optimized for Chrome, Firefox, Safari, and Edge.

### 2.5 Design and Implementation Constraints
- Must comply with housing laws and regulations in India.
- Should support low-bandwidth environments for rural users.
- Ensure cross-platform compatibility and responsiveness.
- Adhere to security and privacy standards (e.g., GDPR).

### 2.6 User Documentation
- User manuals and help guides will be provided for both landlords and tenants.
- Online tutorials and FAQs will be available on the platform.
- Contextual help and tooltips within the application.
- Regular updates to documentation based on user feedback.

### 2.7 Assumptions and Dependencies
- Users have access to internet-enabled devices.
- Users have basic knowledge of using web and mobile applications.
- The platform relies on third-party APIs for payment and location services.
- Continuous internet access for real-time updates and notifications.

## 3. System Features

### 3.1 User Registration and Authentication
- Users should be able to register and log in using email or mobile numbers.
- Support for social media logins (e.g., Google, Facebook).
- Multi-factor authentication for enhanced security.
- Password recovery and account management features.

### 3.2 Property Listing
- Landlords should be able to upload property details, images, and documents for verification.
- Option to schedule property viewings and manage availability.
- Automated property verification process using AI and manual review.

### 3.3 Property Search and Filters
- Tenants should be able to search and filter properties based on location, budget, and amenities.
- Map-based search functionality using Google Maps.
- Advanced filters for property type, size, and other preferences.

### 3.4 Secure Payment Gateway
- A secure payment gateway must be integrated for rental payments.
- Support for multiple payment methods (e.g., credit/debit cards, UPI, wallets).
- Transaction history and receipts for tenants and landlords.

### 3.5 Roommate Matching
- Roommate matching functionality should use AI-based compatibility algorithms.
- Profile creation and preferences for potential roommates.
- In-app communication for roommate discussions and agreements.

## 4. External Interface Requirements

### 4.1 User Interfaces
- Intuitive design with minimal navigation steps.
- Support for both dark and light themes.
- Responsive design for various screen sizes and devices.
- Accessibility features for users with disabilities.

### 4.2 Hardware Interfaces
- Works on devices with 2GB RAM and above.
- Compatible with standard smartphone sensors (e.g., GPS, camera).

### 4.3 Software Interfaces
- Integration with payment gateways like Razorpay or Paytm.
- APIs for property verification and user authentication.
- Integration with third-party services (e.g., Google Maps, email/SMS services).

### 4.4 Communications Interfaces
- Support for push notifications for updates and alerts.
- In-app messaging for communication between users.
- Email and SMS notifications for important updates.

## 5. Other Non-functional Requirements

### 5.1 Performance Requirements
- The system should handle 10,000+ concurrent users.
- Average response time should be under 2 seconds.
- Efficient load balancing and caching mechanisms.

### 5.2 Safety Requirements
- Ensure data backup and recovery mechanisms are in place.
- Compliance with safety regulations for online transactions.

### 5.3 Security Requirements
- Data encryption and secure payment methods.
- Regular security audits and vulnerability assessments.
- Role-based access control and permissions.

### 5.4 Software Quality Attributes
- User-friendly interface with support for multiple Indian languages.
- Scalability to accommodate growing users.
- High availability and minimal downtime.
- Maintainability and ease of updates.

## 6. Other Requirements
- Regular updates and maintenance of the platform.
- Compliance with data protection laws.
- User support and feedback mechanisms.
- Continuous improvement based on user feedback and market trends.

## Appendix A: Glossary
- **MVP**: Minimum Viable Product
- **API**: Application Programming Interface
- **SRS**: Software Requirements Specification
- **UI/UX**: User Interface/User Experience
- **GDPR**: General Data Protection Regulation

---

 **Traceability Matrix** for the **Affordable Housing and Tenant Finder** 

---

| **System Feature**         | **Security**                 | **Performance**             | **Usability**                        |
|----------------------------|-----------------------------|-----------------------------|--------------------------------------|
| **User Registration**       | ↑ Secure User Authentication <br> ↓ Verified Document Storage | ↓ Fast Login Processing             | ↑ Simple and Intuitive Registration Process |
| **Property Listing**        | ↑ Secure Data Upload         | ↓ Quick Image Loading       | ↑ Easy-to-Fill Property Form         |
| **Search Functionality**    | ↑ Filter Privacy (no sensitive data exposed) | ↓ Results Under 2 Seconds            | ↑ User-Friendly Search Filters       |
| **Roommate Matching**       | ↑ Secure Matching Algorithm  | ↓ Matches in Under 30 Seconds | ↑ Intuitive Roommate Suggestions     |
| **Rent Payments**           | ↑ Encrypted Transactions     | ↓ Payment Processing in Real-Time | ↑ Seamless and Clear Payment Flow    |
| **Real-Time Notifications** | ↑ Secure Notification Handling | ↓ Instant Delivery of Notifications | ↑ Easily Accessible Alerts          |
| **Map Integration**         | ↑ Encrypted Location Data    | ↓ Accurate Updates < 5 Seconds | ↑ Easy-to-Use Map with Filters       |
| **Digital Rental Agreement**| ↑ Secure Document Encryption | ↓ Fast Agreement Generation | ↑ Simplified Agreement Forms         |
| **Multilingual Support**    | ↑ Secure Language Switching  | ↓ Fast Language Translations | ↑ Consistent Interface in Multiple Languages |

---

### **Key**:
- **↑**: Emphasizes the **focus on improvement** for the respective non-functional requirement.  
- **↓**: Highlights the **expected performance metric** or timeline for achieving the goal.  

This format combines functional and non-functional requirements into a concise, easy-to-read table, ensuring alignment with the system goals. Let me know if you'd like further clarification!


### **Result:**  
- **Objective Achieved:** The system streamlines the housing process, enhances trust through verification, and reduces the time spent searching for affordable housing.  
- **Outcome:** A scalable, user-centric platform addressing the challenges of the Indian rental market while improving accessibility for all users.  

Would you like further details on implementation or a prototype roadmap?8
