# obrezzzkova-weatherBot
Умный сервис прогноза погоды (telegram bot)
Для создания использовала язык Python + библиотека Flask, загрузила на pythonanywhere. Без сторонних библиотек, предназначенных для написания ботов, т.к. выполняла подобное задание в первый раз и было важно понять механику процессов.

Данные о температуре и скорости ветра, полученные с API, подставляются в  текстовый шаблон "{}°C, ветер {}м/с" и отправляются пользователю.

Сервис - чат-бот, который по заданному пользователем городу, высылает ему ответ.
Данные приходят от пользователя через интерфейс мессенджера.
Формируется и отправляется запрос на https://openweathermap.org 
Полученный ответ используется для формирования ответа пользователю.
Ответ отправляется.
