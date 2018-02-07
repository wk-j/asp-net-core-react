## Bangkok .NET Users Group

This is the repository with the source code and the presentations from the .NET User Group Meetup 06/02/2018. [Single-Page Web Apps using ReactJS and ASP.NET Core](https://www.meetup.com/Bangkok-NET-Users-Group/events/246920822/).

You can find our main page on Meetup.com or click here for more infos about our meetups. [Bangkok .NET Users Group](https://www.meetup.com/Bangkok-NET-Users-Group/). We met at Jetabroad (Thailand) offices on Floor 9, 208 Wireless Road, Bangkok.

## Restore

```bash
npm install --prefix MvcReactApp.Client
dotnet restore MvcReactApp/MvcReactApp.csproj

npm install --prefix MvcReactReduxApp.Client
dotnet restore MvcReactApp/MvcReactReduxApp.csproj
```

## Build

```bash
parcel MvcReactApp.Client/src/boot.tsx -d MvcReactApp/wwwroot
dotnet run --project MvcReactApp

parcel MvcReactReduxApp.Client/src/boot-client.tsx -d MvcReactReduxApp/wwwroot
dotnet run --project MvcReactReduxApp
```