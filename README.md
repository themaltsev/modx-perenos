# MODX ON VPS ПЕРЕНОС БЕЗ БОЛИ

#Ставим права доступа

$ chmod 775 -R /var/www/modx/*

#Нужен Php7.4

### если не видит файлы в диспечере
$ apt install php7.4-mbstring  

# правим пути here >>>>


manager/config.core.php
connectors/config.core.php
config.core.php
core/config/config.inc.php

###########

core/config/config.inc.php

$database_server = 'localhost';
$database_user = 'u1234567_database';
$database_password = 'password';
$dbase = 'u1234567_dbuser';
$database_dsn='mysql:host=localhost;dbname=u1234567_database;charset=utf8';
