# Pierre's Sweet and Savory Treats

#### By: Nick Tse

#### This project demonstrates use of user authentication, authorization, the model-view-controller methodology, many-to-many relationships, and basic database usage with MySQL

## Technologies Used

* C#
* MSTest
* .NET 5 SDK
* ASP.NET Core
* Razor
* HTML
* MySQL
* Entity
* Identity


## Description 

The project is a simple web application that allows a vistor to view the various kinds of treats and flavors Pierre's Bakery has to offer. Additionally, if the user creates an account, they will be able to make updates to the various flavors and treats. The homepage of the app at the root path (localhost:5000/) is a splash page welcoming the user, a brief preface regarding accounts/logging in, and providing them with links to a see treats and/or flavors, following which they may add, edit, or delete, or update the treat/flavor selections.

## Setup/Installation Requirements

* _Clone repository from GitHub_
* _Open your terminal and run the command $ git clone https://github.com/n-tse/PierresTreats.solution_
* _Using the command $ cd PierresTreats, navigate to the PierresTreats directory_
* _Run the command $ dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0_
* _Run the command $ dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2_
* _Run the commmand $ dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore -v 5.0.0_
* _Within the PierresTreats project directory, create a file called appsettings.json_
* _Add the following code to the new appsettings.json file:_ 
  {
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=ntse_pierrestreats;uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
    }
  }
* _Run the command $ dotnet build_
* _Run the command $ dotnet run_
* _In your web browser, type "http://localhost:5000"_
* _The browser should now display the web application for the user to interact with_"

## Known Bugs

* no known bugs

## License

_MIT_

Copyright (c) _2022_ _Nick Tse_