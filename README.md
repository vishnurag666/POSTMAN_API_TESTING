# 🔍 API Testing Project

Welcome to the **API Testing Project** — a robust and well-structured repository where I’ve implemented **comprehensive API tests** using all major HTTP methods with a strong focus on validation and data integrity through assertions.

---

## 📌 Project Overview

This project demonstrates end-to-end API testing using:

- ✅ **GET** – Retrieve resources and validate response structure, status codes, and data integrity.
- ➕ **POST** – Create new resources and assert successful creation and correct response payload.
- ♻️ **PUT** – Fully update existing resources and ensure the changes reflect accurately.
- 🩹 **PATCH** – Partially update a resource and validate targeted updates.
- ❌ **DELETE** – Delete resources and assert successful deletion or appropriate error messages.

Each request includes **assertions to validate**:
- Status codes (e.g., `200 OK`, `201 Created`, `204 No Content`)
- Response body and specific key values
- Headers (like `Content-Type`, `Authorization`)
- Error handling and edge cases

---

## 🚀 Technologies Used

| Tool/Framework | Purpose                          |
|----------------|----------------------------------|
| **Postman**    | Sending requests & writing tests |
| **JavaScript** | Writing test scripts             |
| **JSON**       | Request/Response structure       |

---

## 🧪 Key Test Scenarios

- 🔄 Fetch all records and validate list integrity
- 🔍 Get a specific record and assert on individual fields
- 🧾 Create a new entry and confirm it's successfully stored
- 🛠️ Update entries using both PUT & PATCH methods
- ❌ Delete records and ensure they’re no longer accessible
- 🚧 Negative testing: invalid inputs, missing fields, wrong endpoints

---

## 📁 Folder Structure

