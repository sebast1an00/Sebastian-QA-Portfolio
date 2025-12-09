 API Testing – CRUD Example (Postman)

This module is part of my QA portfolio, where I demonstrate skills in REST API validation, Postman collections, environment variables, test scripts, and proper documentation of test evidence.

 Testing Objective

Validate the functionality of an API that provides CRUD operations (Create, Read, Update, Delete).
All tests were executed using Postman.

Folder Structure
API-Testing/
│── Collection/
│   └── CRUD-Example.postman_collection.json
│
│── Environment/
│   └── CRUD-Env.postman_environment.json
│
│── Evidence/
│   ├── POST_Create.png
│   ├── GET_Read.png
│   ├── PUT_Update.png
│   └── DELETE_Delete.png
│
└── README.md

 Included Files
1. Collection/

Contains the complete Postman collection, including:

Base URL using environment variables

CRUD endpoints

Required headers

Sample request bodies

Automated test scripts (status code, schema, response validation)

2. Environment/

Environment file with variables such as:

base_url

user_id (captured dynamically after creation)

Additional parameters if needed

3. Evidence/

Screenshots showing:

Sent request

Server response

Status codes (200, 201, 404, etc.)

Validation results

🔧 Tested Endpoints (Example)
Method	Endpoint	Description
POST	/users	Create a new user
GET	/users	Retrieve all users
GET	/users/{id}	Retrieve specific user
PUT	/users/{id}	Update a user
DELETE	/users/{id}	Delete a user
 Covered Validations

Status code verification

Response time checks

JSON schema validation

Required fields validation

Dynamic variable extraction

Assertions in Postman test scripts

 Tools Used

Postman – API testing

JSON – Data structures

GitHub – Version control & portfolio
