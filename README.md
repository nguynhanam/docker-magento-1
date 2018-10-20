Docker for magento 1 with all necessary extendsion
- Add your project folder in /src/
- Change nginx file in /nginx/nginx.conf:
 + server.name: with your alias
 + root /src/{Your project}
- Change docker-compose.yml:
 + All volumns line have /src/magento with /src/{Your project}
 + Your database info (database name, database root password)
