### При попытке зайти на localhost:9999 страница не найдена
* создала файлы, размещенные в данном репозитории. В applications.properties Сначала 192.168.0.33 взяла из dockerplayground. Это видно по коммитам. Затем снова исправила на localhost ... окончательно запуталась. 
* в dockerplayground выполняю следующие команды:
    * git clone git@github.com:yoursalex/HomeWorkAqaDocker.git
    * cd HomeWorkAqaDocker
    * cd data
    * apk add openjdk8
    * docker-compose up
До этого момента все работает
* запускаю у себя на машине jar файл командой java -jar db-api.jar

### Ожидаемый результат: 
доступ к данным

### Фактический результат: 
при переходе на http://localhost:9999/api/cards 
Не удается получить доступ к сайту

Судя по всему, у меня какая-то путаница с адресами, ip и вообще всем. 