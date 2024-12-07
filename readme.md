
## **Final Project: User Management System - Feature 9**  

### **Implemented Features and Enhancements**  
1. **Profile Management**  
   - Implemented a feature allowing users to update profile fields such as name, bio, and location through a flexible and user-friendly API.  

   **API Endpoint**:  
   - `/users/updateProfile`  
   Enables users to modify their profile data effortlessly.  

2. **User Status Upgrade**  
   - Developed functionality for managers and admins to update a user's status to "professional."  

   **API Endpoint**:  
   - `/users/{user_id}/updateToProfessional`  
   Empowers admins to manage user designations effectively.  

3. **Email Notification System**  
   - Added automatic email notifications for users when their designation is upgraded to "professional," ensuring they are informed of changes in their status.  

---

### **Technical Updates and Deployment**  
- To resolve initial CI/CD pipeline failures and ensure smooth deployment, the following dependencies were updated:  
  - **PyMySQL==1.1.1**  
  - **starlette>=0.40.0**  
  - **fastapi>=0.103.0**  

---

### **Testing and Quality Assurance**  
- **Added 10+ test cases**:  
   - Comprehensive test coverage was implemented for all user profile updates and professional status upgrade scenarios, validating functionality and handling edge cases.  [Link for 10+ test cases](https://github.com/njit-dl92/user_management/pull/14/files)

**Code and Test Details**:  
- [Feature 9 Implementation - GitHub Repository](https://github.com/njit-dl92/user_management/blob/feature/feature_9_implementation)  

---

### **Issues Resolved**  
Solved 5 major issues to improve the project:  
1.	Application unable to run due to version mismatch [Issue 1 Link](https://github.com/njit-dl92/user_management/issues/18) 
2.	Action execution failing for the feature branch [Issue 2 link](https://github.com/njit-dl92/user_management/issues/19)
3.	Password validation missing during user registration  [Issue 3 link](https://github.com/njit-dl92/user_management/issues/21)
4.	Vulnerability in python-multipart dependency  [Issue 4 link](https://github.com/njit-dl92/user_management/issues/23)
5.	No default role assigned during user creation  [Issue 5 link](https://github.com/njit-dl92/user_management/issues/18)

Details:  
- [GitHub Issues](https://github.com/njit-dl92/user_management/issues)  

---

### **Deployment**  
- Successfully deployed the project to DockerHub.  
  - [DockerHub Repository](https://hub.docker.com/repository/docker/njitdl92/user_management/general)  

- Configured GitHub Actions for automated workflows.  
  - [Successful Workflows](https://github.com/njit-dl92/user_management/actions)  

---

### **Project Links**  
- **GitHub Repository**: [User Management Project](https://github.com/njit-dl92/user_management)  
- **DockerHub Repository**: [DockerHub Link](https://hub.docker.com/repository/docker/njitdl92/user_management/general)  
- **GitHub Actions**: [Successful Workflows](https://github.com/njit-dl92/user_management/actions)  
- **Issues**: [GitHub Issues](https://github.com/njit-dl92/user_management/issues)  
