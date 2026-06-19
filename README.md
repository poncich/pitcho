# Pitcho

**Маркетплейс для поиска инвестиций и размещения стартапов.**

«Авито для стартапов и инвесторов» — простой и быстрый способ свести фаундеров с инвесторами.

## Быстрый старт

```bash
cd pitcho
npm install
npm start
```

Откройте [http://localhost:3000](http://localhost:3000)

## Демо-аккаунты

| Email | Роль | Пароль |
|-------|------|--------|
| founder@pitcho.ru | Фаундер | demo123 |
| investor@pitcho.ru | Инвестор | demo123 |

## Стек

- **Frontend:** HTML, CSS, JavaScript (vanilla)
- **Backend:** Node.js, Express
- **БД:** JSON-файл (без нативных зависимостей)
- **Auth:** JWT + bcrypt

## Функции MVP

- Карточки проектов (создание, просмотр, фильтры)
- Регистрация фаундеров и инвесторов
- Внутренний чат
- Верификация и бейджи доверия
- Библиотека шаблонов документов (NDA, Term Sheet, SAFE)
- Продвижение в топ

## API

| Метод | Путь | Описание |
|-------|------|----------|
| POST | /api/auth/register | Регистрация |
| POST | /api/auth/login | Вход |
| GET | /api/projects | Список проектов (фильтры) |
| POST | /api/projects | Создать проект |
| GET | /api/chat/conversations | Диалоги |
| POST | /api/chat | Отправить сообщение |
| GET | /api/templates | Шаблоны документов |

## Структура

```
pitcho/
├── public/          # Frontend (лендинг + приложение)
│   ├── index.html   # Лендинг
│   ├── app.html     # Маркетплейс
│   ├── css/
│   └── js/
├── server/          # Backend
│   ├── index.js
│   ├── db.js
│   ├── routes/
│   └── middleware/
└── package.json
```

## Слоган

**Pitcho: где сделки начинаются просто**
