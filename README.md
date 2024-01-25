# «Кеширование Redis/memcached»-Абрамов Сергей

---

### Задание 1. Кеширование

Приведите примеры проблем, которые может решить кеширование.

Кэширование, чтобы сократить расходы на базу данных, увеличить пропускную способность и сократить задержку для большинства баз данных, а также повысить производительность облачных и веб-приложений.

Кэширование вывода
Кэширование вывода помогает повысить производительность веб-страниц за счет хранения их полного исходного кода, например, HTML и клиентских скриптов, которые сервер отправляет в браузеры для отрисовки. Каждый раз, когда пользователь просматривает страницу, сервер кэширует выходной код в памяти приложения. Это позволяет приложению обслуживать запросы без выполнения кода страницы или обращения к другим серверам.

Кэширование данных и баз данных
Скорость и пропускная способность баз данных могут иметь ключевое значение для общей производительности приложения. Кэширование базы данных используется для частых вызовов к данным, которые редко изменяются, например к прейскурантам или данным инвентаризации. Это позволяет ускорить загрузку веб-сайтов и приложений, увеличить пропускную способность и сократить задержку при получении данных из серверных баз данных.

Хранение данных пользовательских сеансов
Пользователи приложений часто создают данные, которые необходимо сохранять в течение короткого времени. Хранилище данных в памяти, например, Redis, идеально подходит для эффективного и надежного хранения больших объемов данных сеансов, таких как данные, введенные пользователем, записи корзины покупок или параметры персонализации, с меньшими затратами по сравнению с хранилищем или базами данных.

Архитектуры брокеров сообщений и публикации/подписки
Облачным приложениям часто приходится обмениваться данными со службами, и они могут использовать кэширование для реализации архитектур публикации/подписки или брокера сообщений, которые сокращают задержку и ускоряют управление данными.

Приложения и API
Как и браузеры, приложения сохраняют важные файлы и данные, чтобы при необходимости быстро загрузить их. Кэшированные ответы API устраняют нагрузку на серверы приложений и базы данных или потребность в них, обеспечивая меньшее время отклика и повышенную производительность.





---

### Задание 2. Memcached

Установите и запустите memcached.




![memcached](https://github.com/smabramov/Caching-Redis-and-Memcached/blob/f00026f34ddde0eb7e194c422d7b5cdec61658f0/img/memcached.png)


---

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.



`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями.



`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`