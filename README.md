# InventoryManagementSystem-BackEnd

## Getting Started

Follow these steps to set up and run the project:

1. **Change Server Name in appsettings.json:**
   Open the `appsettings.json` file in your project and locate the `"Server"` configuration under the `"ConnectionStrings"` section. Update the server name to the appropriate value for your database server.

2. **Run Migrations:**
   Open your project in a development environment and follow these commands to run the necessary database migrations:

   ```bash
   Add-Migration InitialCreate
   Update-Database
