# Book Management System

A web-based Book Management System built with **ASP.NET Core Razor Pages** (.NET 10) and **SQL Server**.

## Features

- **Book Catalog**: Browse the complete list of books with title, author, description, publisher, category, and status.
- **Add Books**: Simple form to add new books to the database.
- **Edit Books**: Update existing book details.
- **Delete Books**: Remove books from the system with confirmation.
- **Direct Database Integration**: Uses `Microsoft.Data.SqlClient` for direct SQL querying and management.

## Tech Stack

- **Framework**: ASP.NET Core (.NET 10.0)
- **Frontend**: Razor Pages, Bootstrap 5, jQuery
- **Database**: Microsoft SQL Server / LocalDB (`Microsoft.Data.SqlClient`)

## Getting Started

### Prerequisites

- [.NET 10.0 SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/sql-server) or LocalDB

### Configuration

Update your database connection string in `Books_Managment_System/appsettings.json` if needed:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Data Source=(LocalDB)\\MSSQLLocalDB;Initial Catalog=BMS_DB;Integrated Security=True;Pooling=False;Encrypt=True;Trust Server Certificate=False"
  }
}
```

### Running the Application

1. Open the solution in **Visual Studio** or run via command line:
   ```bash
   cd Books_Managment_System
   dotnet run
   ```
2. Navigate to `https://localhost:7119` (or the configured port) in your browser.
