# MarkelAPITEST
## Endpoints
* api/Companies
* api/Companies/\{id}
* api/Companies/Claims/\{companyId}
* api/Claims
* api/Claims/\{id} -\[Claim id assuming UCR is a string e.g. Claim1]
* api/Claims/\{id} - PUT request
## Assumptions
* UCR is the unique identifier for Claims table
* A company has active insurance based on the fact that field- Active is true and InsuranceEndDate is greater than today's date
* How old a claim is in days depends upon the difference between LossDate and ClaimDate.
