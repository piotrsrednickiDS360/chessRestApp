### How to run the application:
- Docker:
    - open cmd and go to the project directory
    - execute "docker build --tag chess-moves-api ." in command line
    - execute "docker run -d -p 5000:5000 chess-moves-api"
    - visit http://localhost:5000/

- Without Docker:
    - open cmd and go to the project directory
    - execute "./app.py"
    - visit http://localhost:5000/

### Routes:
- http://localhost:5000/api/v1/{chess-figure}/{current-field}
- http://localhost:5000/api/v1/{chess-figure}/{current-field}/{dest-field}

### Additions:
- The application is dockerized
- Multiple tests located in the tests folder were created (for testing classes as well as endpoints)
    - test_models file is tested by using command pytest
    - test_requests file is tested by running the file
- Static Typing was used