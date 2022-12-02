# Checking a bug

To run:


## Running Azure classic package v5.17

1. `cd automation && dotnet run`

Wait for it to complete

1. `dotnet run destroy`

## Running Azure classic package v5.25

1. `cd infra && dotnet add package Pulumi.Azure --version 5.25`
1. `cd ../automation && dotnet run`
