# Student Management System

## Overview
![image](https://github.com/user-attachments/assets/51d926f1-947e-4ac0-96f4-d78345d8492c)

This is a Windows Forms application that manages student records using Entity Framework and a SQL database. It allows users to:

- View a list of students along with their department details.
    
- Search for students by name.
    
- Add new students with ID validation and department selection.
    

## Features

- **Entity Framework Integration:** Uses EF Core to interact with a database.
    
- **Data Display:** Students and departments are displayed in a `DataGridView` and `ComboBox`.
    
- **Search Functionality:** Allows filtering students by name.
    
- **Validation:** Ensures that all required fields are filled and IDs are unique.
    
- **Automatic UI Updates:** Refreshes data after changes.
    

## Technologies Used

- **C#** (WinForms)
    
- **Entity Framework Core**
    
- **SQL Server**
    
- **.NET Framework/.NET Core**
    

## Installation

1. Clone the repository:
    
    ```
    git clone https://github.com/yourusername/your-repo.git
    ```
    
2. Open the project in **Visual Studio**.
    
3. Configure your database connection in `appsettings.json` (if applicable).
    
4. Run the migrations (if needed):
    
    ```
    dotnet ef database update
    ```
    
5. Build and run the project.
    

## How to Use

6. Start the application.
    
7. View the student list in the DataGridView.
    
8. Search for students using the search bar.
    
9. Add a new student by entering details and clicking "Add".
    
10. The table updates automatically with new records.
    

## Contributing

Pull requests are welcome. Please ensure changes follow best practices and include proper validation.

## License

This project is open-source and available under the **MIT License**.

## Author

**Omar Ahmed**
