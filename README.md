=> Scaffold-DbContext "Server=server_Name;Database=HRMS;Trusted_Connection=True;TrustServerCertificate=True" Microsoft.EntityFrameworkCore.SqlServer -OutputDir "Models" -ContextDir "DbContexts" -Project "HRMS.Entities"

Command For Any modification in DB
=> Scaffold-DbContext "Server=server_Name;Database=HRMS;Trusted_Connection=True;TrustServerCertificate=True" Microsoft.EntityFrameworkCore.SqlServer -OutputDir "Models" -force -ContextDir "DbContexts" -Project "HRMS.Entities"
