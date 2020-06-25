This is a repro for [this dotnet watch issue with referenced projects](https://github.com/dotnet/aspnetcore/issues/22219).

It's based on `dotnet new mvc` and `dotnet new razorclasslib`. [More info here](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/target-aspnetcore?view=aspnetcore-3.1&tabs=visual-studio) on using MVC in a class library.

To enable the workaround, rename `Directory.build.targets.workaround` to `Directory.build.targets`.