# Go-CRUD-API

## Dependencies
- GORM
- Go Gin
- MySQL
- GoDotEnv

## Installation
### GORM
```powershell
go get -u gorm.io/gorm
go get -u gorm.io/driver/mysql
```
### Go Gin
```powershell
go get -u github.com/gin-gonic/gin
```
### GoDotEnv
```powershell
go get github.com/joho/godotenv
```

## Running the Project
1) Clone the repo.
2) Install the needed dependencies from the Installation section.
3) Give the credentials of your MySQL database in the .env file under `DB_URL`.
4) Run migrate.go to create a table called `posts` in your database.
5) Run main.go and enjoy!
