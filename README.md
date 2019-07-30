# vets-api-clients

⚠️ **Materials in this repo may be outdated as of July 2019.** This repository contains resources for accessing vets-api as a third-party client. It includes API specifications, sample clients, and general access information.   Anything older than April 2019 may be considered deprecated.  **For the most up-to-date API documentation, please visit [developer.va.gov/explore](https://developer.va.gov/explore).**

Welcome to the repository for consumers of **Department of Veterans Affairs (VA) Lighthouse APIs**.  

If you would like to improve or suggest **edits to API documentation** for the VA APIs, please visit the [APIs repo](https://github.com/department-of-veterans-affairs/vets-api) or the [Developer Portal repo](https://github.com/department-of-veterans-affairs/developer-portal).

Third-party access to vets-api is available to anyone with a developer token (API key), which can be obtained via a [quick application form](https://developer.va.gov/apply).  Production access will be granted later by scheduling a [demo of your application](https://developer.va.gov/go-live) for stakeholders.

Note that the Health (FHIR / Argonaut) APIs for access to Veteran health records are not yet in production; dev access in sandbox using mock patient data is available, and we expect these APIs to be in production by fall of 2019.

## Available Services

### Address Validation*
- The [Address Validation](https://developer.va.gov/explore/verification/docs/address_validation) service (for VA internal use only) provides methods to both standardize and validate addresses.

### Appeals Status*
- Use the [Appeals Status](https://developer.va.gov/explore/benefits/docs/appeals) API to request the status of a Veteran's benefits claim appeal. Currently for VA internal use only.

### Benefits Claims
- Use the [Claims](https://developer.va.gov/explore/benefits/docs/claims) (Auto-Establishment) API to submit a Veteran's benefits claim via EVSS (Electronic Veterans Self-Service), and to request the status of a Veteran's benefits claim.

### Benefits Intake (fka Document Upload Service)
- The [Benefits Intake](https://developer.va.gov/explore/benefits/docs/benefits) API allows authorized third-party systems used by Veteran Service Organizations and agencies to upload claim documents (scanned to PDF) directly to the Veterans Benefits Administration's (VBA) claims intake process.

### Disability Rating
- The [Disability Rating](https://developer.va.gov/explore/verification/docs/disability_rating) API allows third-parties to access the disability rating of a Veteran after receiving authorization to do so using an Open ID Connect flow.

### Facilities
- Use the [Facilities](https://developer.va.gov/explore/facilities/docs/facilities) API to find contact info, location, hours of operation, available services and other relevant information about a specific VA facility. 

### Health (currently dev only)
- Use the [Health APIs](https://developer.va.gov/explore/health/docs/argonaut) to allow Veterans to view their medical records, schedule an appointment, find a specialty facility, and share their information with caregivers and providers.

### Service History
- The [Service History](https://developer.va.gov/explore/verification/docs/service_history) API allows third-parties to access the service history of a Veteran after receiving authorization to do so using an Open ID Connect flow.

### Veteran Confirmation
- The [Veteran Confirmation](https://developer.va.gov/explore/verification/docs/veteran_confirmation) API allows third-parties to request confirmation from the VA of an individual's Veteran status after receiving authorization to do so using an Open ID Connect flow.

\* APIs marked with an asterisk are currently for internal VA use only.

## Requesting Access
If you have any questions after consulting the [API documentation](https://developer.va.gov/explore) and [applying](https://developer.va.gov/apply) for a developer key or OAuth credentials, please email api@va.gov for assistance.  You will receive a human reply within 24 hours.
