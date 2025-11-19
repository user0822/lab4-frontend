# Task Manager Frontend (Lab 4)

## Опис проєкту
Це клієнтська частина системи управління завданнями (Task Manager), розроблена в рамках лабораторної роботи №4.
Застосунок забезпечує сучасний та адаптивний інтерфейс для взаємодії з системою. Реалізовано компонентну архітектуру, маршрутизацію сторінок та підготовлено базу для взаємодії з Backend API.

## Технології
- **Core:** React 18, TypeScript, Vite
- **Styling:** Tailwind CSS, clsx
- **Routing:** React Router v6
- **HTTP:** Axios
- **Code Quality:** ESLint + Prettier

## Встановлення та запуск

### Вимоги
- Node.js 18+
- npm

### Інструкції
```bash
# Клонування репозиторію
git clone [https://github.com/user0822/lab4-frontend.git](https://github.com/user0822/lab4-frontend.git)

# Перехід у папку
cd lab4-frontend

# Встановлення залежностей
npm install

# Створення файлу .env (якщо потрібно)
# VITE_API_URL=[https://task-manager-api-o8is.onrender.com/api](https://task-manager-api-o8is.onrender.com/api)

# Запуск у режимі розробки
npm run dev

# Збірка для продакшену
npm run build
