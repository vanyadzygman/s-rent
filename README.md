# S-Rent: Scooter Rental 

  **Course work in the discipline “Databases”**

## Опис

S-Rent - backend-сервіс оренди електросамокатів. Користувачі орендують самокати на станціях, поїздки тарифікуються, а оплата фіксується в системі. Проєкт демонструє проєктування реляційної БД у 3НФ, складні SQL-запити, транзакційні сценарії створення, оновлення й видалення даних, а також тестування й контейнеризацію.

## Члени команди

  <p align="left">
    <a href="https://t.me/vanyadzygman"><img src="https://img.shields.io/badge/Дзигман_І._О.-ІМ--51-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Дзигман І. О."/></a>
    <a href="https://t.me/saaayq"><img src="https://img.shields.io/badge/Юхимчук_К._С.-ІМ--51-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Юхимчук К. С."/></a>
  </p>

## Технологічний стек

| Компонент | Технологія | Версія |
  |:---|:---|:---:|
  | Мова | Python | 3.14 |
  | Фреймворк API | FastAPI | 0.165.0 |
  | ASGI-сервер | Uvicorn | 0.54.0 |
  | СУБД | PostgreSQL | 18.7 |
  | SQL builder | SQLAlchemy (Core) | 2.0.58 |
  | Драйвер БД | psycopg 3 | 3.3.9 |
  | Тестування | pytest | 9.2.0 |
  | Інфраструктура | Docker, Docker Compose | - |

## Налаштування

  **1. Клонуйте репозиторій**
  ```bash
  git clone https://github.com/vanyadzygman/s-rent.git
  cd s-rent
  ```
  **2. Запустіть сервіси**
  ```bash
  docker-compose up -d
  ```

## Запуск додатку

  ```bash
  [команда запуску]
  ```

## Запуск тестів

  **Усі тести**
  ```bash
  pytest
  ```

  **Конкретний тестовий файл**
  ```bash
  pytest tests/[шлях до файлу]
  ```
  
  > [!WARNING]
  > Інтеграційні тести потребують запущеної БД (`docker-compose up -d`).

## Структура проєкту
  ```
  s-rent/
  ├──
  ```
  
## Приклади API

  <details>
  <summary><b>Приклад запиту й відповіді</b></summary>
  </details>
