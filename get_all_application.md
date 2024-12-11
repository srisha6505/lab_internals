# Application API Reference

## Summary
This document provides a detailed reference for interacting with the `/api/v1/application` endpoint. The endpoint retrieves a list of applications along with their metadata such as application code (`app_code`), description, ID, and name. This API is useful for managing and displaying application-related information within a system.

---

## Request Details

### Endpoint
`https://192.168.0.110:5000/api/v1/application`

### Method
`GET`

### cURL Command
```bash
curl --location 'https://192.168.0.110:5000/api/v1/application'
```

---

## Response Details

The response is an array of JSON objects, where each object represents an application with the following fields:
- `app_code`: The application code (nullable).
- `description`: A brief description of the application.
- `id`: The unique identifier of the application.
- `name`: The name of the application.

### Example Response
```json
[
    {
        "app_code": null,
        "description": "Email Bot for KFintech",
        "id": 6,
        "name": "EMailBot-KFintech"
    },
    {
        "app_code": null,
        "description": "Automate HR services",
        "id": 7,
        "name": "Helpdesk"
    },
    {
        "app_code": null,
        "description": "DMI Finance app",
        "id": 8,
        "name": "DMI"
    },
    {
        "app_code": "default <function generate_random_string at 0x7c4e1e253e20>",
        "description": "Default Application description <function generate_random_string at 0x7c4e1e253e20>",
        "id": 9,
        "name": "nvcarxuKyv"
    },
    {
        "app_code": "default <function generate_random_string at 0x7a3f25147b00>",
        "description": "Default Application description <function generate_random_string at 0x7a3f25147b00>",
        "id": 10,
        "name": "HLLTXiXavR"
    },
    {
        "app_code": "default <function generate_random_string at 0x7a3f25147b00>",
        "description": "Default Application description <function generate_random_string at 0x7a3f25147b00>",
        "id": 11,
        "name": "MimDIwfRaj"
    },
    {
        "app_code": "MID-MIS",
        "description": "MIDLAND MIS",
        "id": 12,
        "name": "MIDLAND MIS"
    },
    {
        "app_code": null,
        "description": null,
        "id": 1,
        "name": "Helpdesk"
    },
    {
        "app_code": "breeze-mis",
        "description": "Manage user system, and get detailed reports",
        "id": 3,
        "name": "Breeze-mis"
    },
    {
        "app_code": null,
        "description": "Monitoring Systems",
        "id": 4,
        "name": "DivyaDrishti"
    },
    {
        "app_code": null,
        "description": "Automate Finance services",
        "id": 5,
        "name": "Awesome Finance"
    },
    {
        "app_code": null,
        "description": "MIS Dashboard application",
        "id": 2,
        "name": "Breeze-MIS-KFintech"
    }
]
```

---



