
1) ЗАПРОС ДЛЯ РЕГИСТРАЦИИ
```
{
  "user": {
    "username": "kukoracha",
    "email": "kukurocha@gmail.com",
    "password": "kukoracha123"
  }
}
```
ОТВЕТ ОТ СЕРВЕРА
```
{
    "user": {
        "email": "kukurocha@gmail.com",
        "username": "kukoracha",
        "bio": null,
        "image": "https://api.realworld.io/images/smiley-cyrus.jpeg",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6Imt1a3Vyb2NoYUBnbWFpbC5jb20iLCJ1c2VybmFtZSI6Imt1a29yYWNoYSIsImlhdCI6MTY2ODQzNjk0NywiZXhwIjoxNjczNjIwOTQ3fQ.DVU_dt8UEZV0KF7wat-QleF7wSNmlSc-EnsdSPecGDo"
    }
}
```

2) ЗАПРОС НА АВТОРИЗАЦИЮ
```
{
  "user": {
    "email": "kukurocha@gmail.com",
    "password": "kukoracha123"
  }
}
```
ОТВЕТ ОТ СЕРВЕРА
```
{
    "user": {
        "email": "kukurocha@gmail.com",
        "username": "kukoracha",
        "bio": null,
        "image": "https://api.realworld.io/images/smiley-cyrus.jpeg",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6Imt1a3Vyb2NoYUBnbWFpbC5jb20iLCJ1c2VybmFtZSI6Imt1a29yYWNoYSIsImlhdCI6MTY2ODQzNzQ0NywiZXhwIjoxNjczNjIxNDQ3fQ.0JdL71ojT12gh7oS-HwHUr4Vg4B-RQBMkCx_MTjL3iY"
    }
}
```
3) ПОЛУЧЕНИЕ ДАННЫХ ТЕКУЩЕГО ПОЛЬЗОВАТЕЛЯ 
    ОТВЕТ ОТ СЕРВЕРА:
```
    {
        "user": {
            "email": "kukurocha@gmail.com",
            "username": "kukoracha",
            "bio": null,
            "image": "https://api.realworld.io/images/smiley-cyrus.jpeg",
            "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6Imt1a3Vyb2NoYUBnbWFpbC5jb20iLCJ1c2VybmFtZSI6Imt1a29yYWNoYSIsImlhdCI6MTY2ODQzOTcyMiwiZXhwIjoxNjczNjIzNzIyfQ.6CWuNwaFCfMFaMsMTkaZQIVXIkhLW3WWnTU6AyDE7K0"
        }
    }
 ```
