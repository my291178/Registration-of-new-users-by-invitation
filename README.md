# Сервис регистрации пользователя по приглашению 
На главной странице: 
  1. для авторизованных (с кнопкой “Выйти” и формой для приглашения новых пользователей)
  2. для остальных (с формой ввода логина и пароля)

При создании инвайта уходит письмо на email.
В письме располагается ссылка, при переходе по которой открывается форма установки логина и пароля.
После регистрации создается и авторизуется пользователь в системе. 

Инвайт:
 - уникальный
 - не может быть использован повторно
 - после использования привязан к пользователю

 Использована база sqlite

Логин/пароль для входа в систему: admin/admin

Для корректной работы приложения необходимо дополнительно установить пакеты:
- Flask
- Flask-Mail
- Flask-UUID
- uuid
