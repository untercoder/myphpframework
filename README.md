Тестовый php фреймфорк для понимания устройства Laravel/Yii2.

Реализация учебных материалов: https://www.youtube.com/watch?v=nGHfiWjIDr8&list=PLD-piGJ3Dtl1gX1wh22vBeeg6gMP1VlnW
Кол-во уроков: 31 каждый 40 мин (21 час).

В папке app - находяться все пользовательские модули, контроллеры и предствления(MVC).

В папке public - как правило находится точка входа (front controller),
также в папке находятся все внешние ресурсы: скрипты, кртинки, css/html.

В папке vendor - находится ядро фреймворка(папка core) и папка с зависимостями libs.

Два файла .htaccess перенаправляют все запросы в public/index.php

Все запросы к серверу хранятся в супер глобпльном массиве $_SERVER["QUERY_STRING"];

/vendor/core/Router.php - класс который реализует маршрутизатор.

В папке libs хранятся вспомогательные функции и классы

Модифицировал rootMatch() для работы с регулярными выражениями




