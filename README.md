# Инструкция по запуску автотестов
Автотесты написаны на Python и используют библиотеку pytest. 

### Установка зависимостей

Выполните в корне проекта:
```bash
pip install -r requirements.txt
```
# API-tests(2.1)
**Запуск тестов**

Выполните команду:
```bash
pytest avito-api-tests/ -v
```
### Дополнительно

**Только E2E-сценарии**

Выполните команду:
```bash
pytest avito-api-tests/ -v -m e2e
```
**Проверка и форматирование кода**

Проверить код на ошибки стиля:
```bash
flake8 avito-api-tests/
```
Автоматически отформатировать код:
```bash
black avito-api-tests/
```
Проверить, что код отформатирован:
```bash
black --check avito-api-tests/
```


