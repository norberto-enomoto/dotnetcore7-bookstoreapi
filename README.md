
# Example Microservice using C# and dotNetCore 7

https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-7.0&tabs=visual-studio-code


## Command to run mongo in container
  
- docker run --name some-mongo -p 27017:27017 mongo:latest
  
- docker exec -it <container-id> /bin/bash  

- mongosh -u root -p password

dotnet add BookStoreApi.csproj package Swashbuckle.AspNetCore -v 6.2.3
dotnet add package MongoDB.Driver

http://0.0.0.0:5000/swagger/index.html