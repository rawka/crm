# Основной функционал
## Функционал для менеджера
1. Ведение сделки
2. Автоматическое прикрепление записи звонка к контрагенту
3. Отчеты по продажам
4. Воронка продаж
5. История переписок клиентов в мессенджерах и по email, возможность общения из CRM
6. Мониторинг социальных сетей на предмет комментариев для быстрого реагирования
7. Итерфейс мониторинга ведения сделок на текущий момент и за период времени
8. Система уведомлений о различный событиях
9. Напоминания совершить действия с клиентами
10. Отзывы о сделке
11. Сохранения данных в excel
12. Календарь с интеграцией gmail (по всем продуктам + личные)
13. Хранение контента (изображения, исходники) для каждого контрагента (возможно интеграция с Яндекс)
14. Возможность интегрировать с сайтами

## Функционал для техника
1. Просмотр и фильтрация технических заданий
2. Добавление фото и комментариев к техническим заданиям

## Функционал для исполнителя
1. Просмотр технического задания (комментарии?)

# Набор сущностей базы данных
- Пользователи
- Роли
- Контрагенты
- Контакты
- Продукты
- Характеристики продуктов
- Сделки
- Календарь
- Звонки
- Переписка
- Комментарии
- Отзыв
- Уведомления
- Материалы (медиа)
- Настройки

# Набор полей каждой сущности

## Пользователи
- Логин
- Пароль
- ФИО
- Соц сеть? (telegram)
- Gmail ??

## Роли
- Роль

## Контрагенты
- Наименование
- Контакты (ссылки)
- Медиа (ссылки)

## Контакты
- ФИО
- Соц сеть? (telegram)
- Телефон
- EMail

## Продукты
- Наименование
- Характеристики (ссылка)

## Характеристики продуктов
- Корпус
- Фон

## Сделки
- Статус
- Контрагент (ссылка)
- Контакт (ссылка)
- Продукт (ссылка)
- Характеристики (ссылки)
- Дата проведения (календарь)
- Место и адрес проведения (попробовать вставить карту и базу адресов)
- Время прихода гостей
- Медиа (ссылка)
- Время начало работы
- Место расположения
- Часы работы
- Дополнительные параметры (улица, дети, имена, рамка)
- Деньги
- Аванс
- Тип мероприятия (перчеслить все типы: )
Добавить вычисляемы поля по времени и деньгам

## Календарь
Интеграция с Gmail

## Звонки
- Дата и время
- Контакт (ссылка)
- Контрагент (ссылка)
- Запись (ссылка)

## Переписка
- Дата и время
- Сообщение
- Контрагент (ссылка)
- Контакт (ссылка)

## Комментарии
- Сделка (ссылка)
- Дата и время
- Комментарий
- Файлы?

## Отзыв
- Сделка (ссылка)
- ???
Очень напоминает комментарий!

## Уведомления
Структура зависит от типа уведомлений, но скорее всего надо хранить в БД как лог

## Материалы (медиа)
- Материал (ссылка)

## Настройки
Пока что нечего настраивать

## Лиды
- Статус
- Контрагенты
- Контакты
- Продукт
- Дата мероприятия
- Дата обращения
- Деньги
- Комментарии

# Интерфейсы
[Ссылка](https://ninjamock.com/s/DVSHVKx)

# Дополнительно
Пожелания и критика после закрытия сделки 

Добавить поиск 

