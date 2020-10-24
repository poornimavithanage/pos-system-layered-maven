# POS System [Layered Architecture with Maven]

In this **POS System** has all the functionalities of a POS system, like customer adding,item management,order placing,order viewing and order searching.It consists of five main parts;

    * Manage customers
    * Manage items
    * Placeorders
    * View orders
    * Search orders

## Dependencies

* [JFoenix](https://mvnrepository.com/artifact/com.jfoenix/jfoenix/8.0.10) - is an open source Java library, that implements Google Material Design using Java components.
* [MySQL Connector](https://mvnrepository.com/artifact/mysql/mysql-connector-java/8.0.21) - MySQL Connector/J is the official JDBC driver for MySQL.

## Maven

> Maven is project/build management tool.
  
  Instead of downloading and placing the jars manually in the project, we can use maven to automate the process. We can define the dependency in the **pom.xml (Project object model)**. Maven requires internet to download the jars, which is a one time process.

## Database

Find Database Configuration From src/main/java/lk.ijse.dep.pos.db.DBConnection and set your Database name,user name and password.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
