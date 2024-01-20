#MySQL script
CREATE DATABASE proshop;

CREATE TABLE products (
    id INT AUTO_INCREMENT NOT NULL,
    name VARCHAR(255) NOT NULL,
    description TEXT,
    price DOUBLE,
    PRIMARY KEY (id)
);
