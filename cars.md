<!-- auto usate messe in vendita da un concessionario -->
<!-- auto in generale, non la singola auto -->
<!-- campi che tutte le auto hanno in comune -->
<!-- Sto registrando l'auto fisica o l'esistanza di questa auto? -->

| name             | type         | attribute      | index       |
| ---------------- | ------------ | -------------- | ----------- |
| id               | BIGINT       | NOT NULL, A.I. | PRIMARY KEY |
| car_brand        | VARCHAR(50)  | NOT NULL       |
| condition        | VARCHAR(50)  | NOT NULL       | INDEX       |
| color            | VARCHAR(20)  | NULL           |
| kilometers       | FLOAT(10, 3) | NOT NULL       | INDEX       |
| max_speed        | INT          | NULL           |
| year_of_purchase | DATE         | NOT NULL       |
| type_of_fuel     | VARCHAR(20)  | NULL           |
| usage            | VARCHAR(20)  | NOT NULL       |
| accessories      | TINYINT      | NULL           |
