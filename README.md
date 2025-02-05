# Исходный код телеграм бота 11 Б

## Описание функционала

### Основной функционал:
- Просмотр домашнего задания (ДЗ) из системы "Сетевой Город".
- Изменение пользовательской группы обучения.

### Административные команды:
- Выбор канала для рассылки ДЗ из существующих групп.
- Настройка времени для автоматической рассылки (в формате ЧЧ:ММ).

## Зависимости

- **[NetSchool API](https://github.com/nm17/netschoolapi)**: основная библиотека для взаимодействия с системой "Сетевой Город".
- **[Aiogram](https://docs.aiogram.dev/)**: современный и полностью асинхронный фреймворк для работы с Telegram Bot API на Python.
- **[HTTPX](https://github.com/encode/httpx)**: асинхронный HTTP-клиент для Python, необходимый для работы NetSchool API.
- **[Python Dotenv](https://github.com/theskumar/python-dotenv)**: библиотека для работы с переменными окружения, упрощающая хранение конфиденциальной информации.

## Примечание
Этот бот предназначен исключительно для использования учениками и администрацией группы 11 Б. Пожалуйста, убедитесь, что доступ к боту защищён, чтобы избежать утечки персональных данных.
