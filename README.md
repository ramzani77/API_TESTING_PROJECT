# 🔗 API Testing Project (Postman + Automation)

## 📌 Project Overview

This project focuses on testing REST APIs using Postman and validating API responses for correctness, reliability, and performance. It includes automated test scripts for various HTTP methods and response validations.

---

## 🚀 Tech Stack

* Postman
* Newman (CLI runner)
* JavaScript (Postman scripts)
* REST APIs

---

## 🧪 Test Coverage

* GET Requests → Fetch data from API
* POST Requests → Create new resources
* PUT Requests → Update existing data
* DELETE Requests → Remove resources

---

## ✅ Validations Performed

* Status Code Validation (200, 201, 400, 404)
* Response Body Validation
* JSON Schema Validation
* Response Time Checks
* Header Validation

---

## 📂 Project Structure

```id="api123"
Postman Collection → API test cases
Environment File → Variables setup
Reports → Newman execution reports
```

---

## ▶️ How to Run Tests

### Using Postman:

1. Import collection into Postman
2. Select environment
3. Click **Run Collection**

---

### Using Newman (CLI):

```id="api456"
npm install -g newman
newman run collection.json
```

---

## 📊 Reporting

* Newman HTML reports generated after execution
* Console logs for debugging

---



---

## 💡 Key Learnings

* API request/response validation
* Writing test scripts in Postman
* Handling dynamic data in APIs
* Automating API tests using Newman

---

## 👤 Author

**Sameer Ramzani**
GitHub: https://github.com/ramzani77
