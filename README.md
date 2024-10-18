# Backend Setup Instructions

## 1. Clone the Repository
```bash
git clone <repository-url>
cd backend
```
## 2. Install Dependencies
```bash
npm install
```
## 3. Add your credentials
```bash
create database and add your database credentials correctly
add your auth0 credentials to verifyJwt funtion correctly
  jwksUri: "https://YOUR_AUTH0_DOMAIN/.well-known/jwks.json"
  audience: "Replace with your audience in auth0 api",
  issuer: "https://YOUR_AUTH0_DOMAIN/", 
```
## Run the Server
```bash
npm start

```

