# 🚀 AppConfig²: App Configuration & Testing Tool

**Test, Debug, and Optimize Microsoft Entra™ ID App Registrations**

🔗 **Live Demo & More Info**: [appconfig.app](https://appconfig.app)
<!-- 📖 **Documentation**: [Visit Docs](https://appconfig.app/docs) -->
🔗 **[Live Demo](https://appconfig.app/#demo)**  

## 🔥 Key Features
✅ **Manage Redirect URIs** - Add or remove URIs for troubleshooting authorization issues.  
✅ **View & Decode Tokens** - Inspect OAuth2 and SAML tokens in real-time.  
✅ **Customize Token Claims** - Modify token claims for security testing.  
✅ **Register & Modify Applications** - Create and configure Entra ID app registrations.  
✅ **Test Authentication Flows** - Validate OIDC/OAuth and SAML flows.  
✅ **Embedded Graph Explorer** - Drill into app configurations via Microsoft Graph API.  
✅ **Restore Configurations** - Quickly revert tested apps to their original settings.  


## 🛠️ How It Works
1️⃣ **Sign in** with your Microsoft Entra ID account.  
2️⃣ **Test & Debug** - Modify app settings, inspect tokens, and analyze configurations.  
3️⃣ **Restore & Secure** - Revert app settings and ensure compliance.  

## 👥 Who Should Use AppConfig²?
👨‍💻 **Developers** - Test authentication flows and debug app registrations.  
🔐 **Security Engineers** - Validate security configurations and permissions.  
🛠️ **IT Administrators** - Manage Entra ID app registrations efficiently.  
🎯 **L3 Support Teams** - Troubleshoot complex authentication issues.  

## 🚀 Try It Now
🔗 **[Live Demo](https://appconfig.app)**  

## ⚠️ Disclaimer
This tool is **not affiliated with or endorsed by Microsoft**. "Entra ID" is a trademark of Microsoft Corporation.

## 📩 Want Early Access?  
DM me on [LinkedIn](https://www.linkedin.com/in/tonino-filipovic-7a501b1/) 

---

## 📜 **Detailed Information**

### **User Authentication & Authorization**
- Secure login via **MSAL (Microsoft Authentication Library)**.
- Supports **popup-based authentication**.
- Retrieves **user display name** upon login.
- Handles **MSAL initialization and errors gracefully**.

### **Application Listing & Filtering**
- Fetches a **list of all registered applications** from **Microsoft Graph API**.
- Allows filtering based on **application type (SPA or Web)**.
- Displays applications with an intuitive, easy-to-navigate UI.

### **Application Selection & Configuration**
- Select an application from the list and view its **detailed settings**.
- Configure **authentication methods, token lifetimes, and redirect URIs**.
- Modify **App Roles, API permissions, and owners**.

### **Application Testing**
- Provides a **real-time testing environment** for authentication & authorization.
- Allows users to **modify settings dynamically and test their effects immediately**.
- Supports **user impersonation & permission validation**.
- Displays **decoded access tokens** for verification.

### **Token Decoding & Visualization**
- Decodes **JWT access tokens** and extracts key claims.
- Displays token contents in a **formatted, easy-to-read window**.
- Supports **comparison between main & test accounts**.

### **Graph Explorer Integration**
- Provides an **interactive API tester** for Microsoft Graph.
- Supports **GET, POST, PATCH, DELETE** methods.
- Displays **formatted API responses**.

### **Authentication Flow Tester**
- Tests **various authentication scenarios**.
- Validates **token generation and permission assignments**.

### **New Application Registration**
- Enables **direct registration of new applications**.
- Supports **SPA and Web applications**.
- Configures **initial Redirect URIs and Sign-In Audience**.

### **Backup & Restore**
- Create a **backup of current application settings** before modifying.
- Restore settings **in case of misconfigurations**.

### **Application Role & API Permission Management**
- **Add, modify, and remove App Roles** dynamically.
- **Manage API permissions**, including **scopes and delegated permissions**.
- Uses **Graph API for real-time permission resolution**.

### **Owner Management**
- Assign and remove **application owners**.
- Resolves owner details **via Microsoft Graph API**.

---


