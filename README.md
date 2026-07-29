# ArchaeologicalSystem (Backend)

## Tech Stack

**Language:** Python <br>
**Framework:** FastAPI <br>
**ORM:** SQLAlchemy <br>
**Validation:** Pydantic <br>
**Testing:** Pytest <br>
**Security:** JWT Authentication, RBAC <br>

## Contributions

 <br><br>**Models & Schemas:** Designed and implemented SQLAlchemy ORM models and Pydantic schemas for artifacts, locations, scientific claims, and documents according to technical specifications. Managed relationships between database entities and cleaned up legacy structures.
 <br><br>**Service Layer & API:** Implemented a service layer to decouple business logic from API routers. Developed CRUD endpoints for artifacts and documents, including soft-delete functionality and filtering.
 <br><br>**Access Control (RBAC):** Configured role-based access control and automated user context injection via JWT tokens.
 <br><br>**Testing:** Wrote and executed unit and integration tests using `pytest` within a virtual environment.

---

# ArchaeologicalSystem (Бэкенд)

## Стек технологий

**Язык:** Python <br>
**Фреймворк:** FastAPI <br>
**ORM:** SQLAlchemy <br>
**Валидация:** Pydantic <br>
**Тестирование:** Pytest <br>
**Безопасность:** JWT-авторизация, RBAC <br>

## Вклад и задачи

 <br><br>**Модели и схемы:** Спроектировал и реализовал ORM-модели (SQLAlchemy) и схемы (Pydantic) для артефактов, локаций, научных заявок и документов в соответствии с ТЗ. Настроил связи между сущностями и удалил устаревшие структуры данных.
 <br><br>**Сервисный слой и API:** Вынес бизнес-логику в сервисный слой, отделив её от роутов. Реализовал эндпоинты для работы с артефактами и документами (включая CRUD, мягкое удаление и фильтрацию).
 <br><br>**Контроль доступа (RBAC):** Настроил ролевую модель и автоматическое подтягивание ID автора из токена пользователя.
 <br><br>**Тестирование:** Написал и успешно прогнал тесты с помощью `pytest` в виртуальном окружении.
