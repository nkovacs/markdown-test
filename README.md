`` mysql -h 0.0.0.0 -P `docker-compose port db 3306 | cut -d: -f2 -u php -p` ``

| Foo | Bar |
| --- | --- |
| `` mysql -h 0.0.0.0 -P `docker-compose port db 3306 | cut -d: -f2 -u php -p` `` | this is broken |
| backslash \| escape | this is also broken |
| backtick `|` escape | this is also broken |
