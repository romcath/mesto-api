# Сервер для проекта Mesto

###### Версия проекта: 0.0.6

## О проекте
API для сервиса размещения фотографий Mesto.
> Это учебный проект, сделан в [Яндекс.Практикуме](https://praktikum.yandex.ru). Код проходил код-ревью.

Реализована логика:
1. По локальному адресу ```localhost:3000``` сервер загружает фронтенд проекта Mesto;
2. В ответ на запрос ```GET localhost:3000/users``` сервер вернёт JSON-объект из файла ```users.json```;
3. В ответ на запрос ```GET localhost:3000/cards``` сервер вернёт JSON-объект из файла ```cards.json```;
4. В ответ на запрос ```GET localhost:3000/users/8340d0ec33270a25f2413b69```, сервер вернёт JSON-объект пользователя с переданным после ```/users``` идентификатором;
5. Если пользователя с запрошенным идентификатором нет, API вернёт ```404``` статус ответа и JSON: ```{ "message": "Нет пользователя с таким id" }```;
6. При запросе на несуществующий адрес, API вернёт ```404``` статус ответа и JSON: ```{ "message": "Запрашиваемый ресурс не найден" }```.

## Установка проекта
Клонируйте репозиторий на компьютер:

```git clone https://github.com/romcath/praktikum_backend-mesto.git```

Установите зависисмости:

```npm install```

Запустите сервер:

```npm run start```


## Стек технологий
HTML, CSS, JavaScript, Webpack, GIT, Node.js, Express.js
