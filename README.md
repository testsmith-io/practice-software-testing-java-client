# API Client Generators for Software Testing Practice
Welcome to the **API Client Generators Repository!**
This project provides **Java clients** generated from multiple versions of an API using **OpenAPI Generator**. The clients are useful for **practicing API testing**.

## **🚀 Features**
✅ **Auto-generated Java Clients** for API versions `v1`, `v2`, `v3`, `v4`, `v5`, and `with-bugs`  
✅ **Maven-ready** clients published on [Maven Central](https://mvnrepository.com/)  
✅ Ideal for **QA engineers, software testers, and developers**

## **📂 Project Structure**
```
api-clients/
│── pom.xml  # Parent POM (manages all client modules)
│── v1-client/
│   ├── pom.xml
│── v2-client/
│   ├── pom.xml
│── v3-client/
│   ├── pom.xml
│── v4-client/
│   ├── pom.xml
│── v5-client/
│   ├── pom.xml
│── with-bugs-client/
│   ├── pom.xml
```

Each module contains:
- A **Java client** for interacting with the API.

# 🔧 How to Use
## Add as a Dependency (via Maven)
These clients are published on **Maven Central**. To use them in your project, add the corresponding dependency:

```xml
<dependency>
    <groupId>io.testsmith.practicesoftwaretesting</groupId>
    <artifactId>v5-client</artifactId>
    <version>1.0.0</version>
</dependency>
```
Replace `v1-client` with `v2-client`, `v3-client`, etc., as needed.


## 📌 Useful Resources
- 📖 [OpenAPI Generator Docs](https://openapi-generator.tech/docs/installation)
- 📖 [Maven Central Repository](https://mvnrepository.com/)
