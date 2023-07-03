# Sales-Simplify-Assignment
Sales Simplified assignment for backend node js developer

## API testing details 

### 1. Get all contact record :: ( http get method )
        api -> http://localhost:8080/contact
        
### 2. Get contact record by id :: ( http get method )
        api -> http://localhost:8080/contact/id 
         working eg :: http://localhost:8080/contact/2
        
### 3. Delete contact record by id :: ( http delete method )
        api -> http://localhost:8080/contact/id 
         working eg :: http://localhost:8080/contact/2

### 4. Add contact record by id :: ( http post method )
        api -> http://localhost:8080/contact

        JSON Payload :: ( Note :: please make sure the input is as per the assignment pdf )
        {
          "firstName": "abc",
          "lastName": "abc",
          "gender": "MALE",
          "address": {
            "line1": "Mandatory, Any String/Symbol/Characters, Min. Length 8",
            "line2": "Optional, Any String/Symbol/Characters, any length",
            "city": "aaaa",
            "country": "india",
            "zipCode": "0000001"
          },
          "email": "abc@gmail.com",
          "phone": "0000000001"
        }

### 5. Update contact record by id :: ( http put method )
        api -> http://localhost:8080/contact/id
        eg :: http://localhost:8080/contact/2
        
        JSON Payload :: ( Note :: please make sure the input is as per the assignment pdf )
        {
          "firstName": "abc",
          "lastName": "abc",
          "gender": "MALE",
          "address": {
            "line1": "Mandatory, Any String/Symbol/Characters, Min. Length 8",
            "line2": "Optional, Any String/Symbol/Characters, any length",
            "city": "aaaa",
            "country": "india",
            "zipCode": "0000001"
          },
          "email": "abc@gmail.com",
          "phone": "0000000001"
        }
