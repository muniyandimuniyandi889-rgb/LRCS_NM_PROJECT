# LRCS_NM_PROJECT
A ServiceNow-based project that automates the laptop request process for employees using a dynamic Service Catalog item. The project includes catalog form creation with conditional fields, UI policies, client-side scripting, update set management, and testing for deployment across instances.

# Laptop Request Catalog Item - ServiceNow Project

## Project Overview
This project simplifies the process of requesting laptops within an organization by leveraging **ServiceNow Service Catalog** capabilities. It provides a **dynamic form** for employees to request laptops with features like conditional fields, a reset button, and easy migration using update sets.  

The goal is to replace the manual, error-prone laptop request process with an automated, user-friendly solution that improves efficiency and accuracy.

---

## Features
- **Dynamic Catalog Item** for Laptop Requests
- **Conditional Field Visibility**: Accessories details appear only when needed
- **Form Reset Functionality** using UI Actions
- **Update Set Export/Import** for deploying changes to other instances
- **Testing & Validation** for smooth implementation
- **User-friendly Interface** to enhance employee experience

---

## Skills & Technologies Used
- ServiceNow Administration
- Service Catalog Management
- UI Policies & Client-Side Scripting
- Update Set Management
- Testing & Validation
- Team Collaboration & Documentation

---

## Project Structure
- **Catalog Item Creation** – Laptop Request Form
- **Variables** – Laptop Model, Justification, Additional Accessories, Accessories Details
- **UI Policy** – Conditional display & mandatory settings for accessories details
- **UI Action** – Reset button for clearing the form
- **Update Set** – For exporting/importing configurations between instances
- **Testing** – Validating functionalities after migration

---

## Setup Instructions
### 1. Create ServiceNow Instance
- Sign up at [ServiceNow Developer](https://developer.servicenow.com)
- Request a Personal Developer Instance (PDI)

### 2. Create a Local Update Set
- Name: `Laptop Request`
- Make it the current update set for tracking all changes

### 3. Create Catalog Item
- Name: `Laptop Request`
- Catalog: `Service Catalog`
- Category: `Hardware`
- Add variables: Laptop Model, Justification, Additional Accessories, Accessories Details

### 4. Create UI Policy & Actions
- Show/Hide `Accessories Details` based on the `Additional Accessories` checkbox
- Add a Reset button using a client-side UI Action script

### 5. Export & Import Update Set
- Export the update set as XML
- Import and commit it on another instance

### 6. Test the Catalog Item
- Validate the form behavior and reset functionality
- Ensure all fields work as expected in the target instance

---

## How to Use
1. Go to **Service Catalog** → **Hardware** → **Laptop Request**
2. Fill in the required fields
3. Check **Additional Accessories** if needed
4. Click **Reset** to clear the form
5. Submit the request once ready

---

## Team Members
- **R. Vijay Kumar** (Team Leader)
- **R. Muniyandi**
- **E. Gokul Rajan**
- **K. Tamilarasan**

---

## Conclusion
This project successfully streamlines the laptop request process using ServiceNow Service Catalog. It reduces manual effort, enhances user experience, and ensures easy migration and deployment.

---

## License
This project is for academic and learning purposes. No commercial license provided.
