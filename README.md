# 📗 Table of Contents
- [API Documentaion](#jms-api)
  - [Data Format](#data-format)
  - [Endponts](#endpoint)
      - [Authentication](#auth)
      - [PUT_TEXT_HERE ](ID_HERE)
      - [PUT_TEXT_HERE ](ID_HERE)
      - [PUT_TEXT_HERE ](ID_HERE)

`Consider this as html link navigation using element id lets define the actual documentation using <a name="jms-api"></a> which is the same name as [API Documentaion](#jms-api) both use jms-api`

# JMS api documentation <a name="jms-api"></a>
This is a documentation for JMS API. 
## Data format for input and output request <a name="data-format"></a>
For every `POST` and `PUT/PATCH` requests, you can provide data in JSON format. For GET requests, the API will return data in JSON format. For all requests, you must include the Authorization token as a `Bearer token`. The Authorization header should be formatted as follows:

## API Endpoints <a name="endpoint"></a>
> Note: For Every endpoint use `https://jms.godaddy.com` as a root URL.

### Authentication <a name="auth"></a>
#### How to get the API KEY? <a name="api-key"></a>
To get the api key you need to authenticate using `user_name` and `password` and send `get` request to

 `/api/v1/user/login`



 if you want to write JSON code use json like below 
 ```json
 {
    "token": "API_KEY",
    "user": {
        "id": "..",
        "username": "..",
        "role": ".."
   }
}
 ```

 if you want to write javascript code use javascript like below 

 ```javascript

 const api = ()=>{
  console.log("API DOC");
 }
```