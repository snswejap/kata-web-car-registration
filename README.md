# Kata Rego

> Spend 15 to 30 minutes daily to work on the Kata
> 
> Come  up with your own Kata and share with the team
> 
> To increase difficulty level, only  use keyboard shortcuts (minimum use of mouse)

## Part 1

Build an API for the following:

1. Should be able to save car registration number (rego) and expiry date

2. Should return Bad Request if rego or expiry date not supplied

3. Should return Bad Request if expiry date not in the format `YYYY-MM-DD`
   
   `Y` and `M` and `D` must be number
   
   No date validation required (i.e. doesn't have to be a valid date)
   
4. Should return Internal Server Error with error message if service
   layer return error.
