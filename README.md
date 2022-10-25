# sql--

1) SELECT COUNT(*) FROM INFORMATION_SCHEMA.TABLES WHERE TABLE_TYPE = 'BASE TABLE';
2) SELECT table_name FROM information_schema.tables WHERE table_schema = 'p518138-lyc';
3) SELECT * FROM users;
4) SELECT * FROM grades;
5) SELECT * FROM users.grades WHERE users.user_id = grades.user_id
6) SELECT * FROM users WHERE fam = 'Ложанова'
