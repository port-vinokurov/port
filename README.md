Всем привет. Автоматизирую Северную трибуну - одно из общественных объединений. Цель, устав и задачи объединения опубликованы в разделе Кто мы? на сайте. 
Сделал тестовый стенд. Для наглядной демонстрации функционала. Данный комплекс разработан, ра мной с "нуля"
Данный программный комплекс состоит из четырех приложений.
1) Сайт
2) Админка сайта
3) Телеграм бот
4) Админка телеграм бота.

Архитектурно, сайт и телеграм бот 
Там получается комплекс: сайт+админка+телеграмбот. К сайту прикручена telegram api auth. Сайт адаптивный.

Стек грубо:
python
django
postgres
aiogram
redis

Кратенько о функционале:

Сайт:
Авторизация на сайте через telegram api auth. Это означает что не нужно вводить логин/пароль. И у нас есть всегда связь с пользователем для рассылки предложений.
Админка совместная с админкой бота.
Публикация информации из телеграм канала на сайте и обратно.
И получения обратной связи.

Телеграм бот:
Турниры
Анкеты
Тренировки
Другие мероприятия типа экскурсии, концерты
Платежный модуль (карты, телефоны), если несколько чтобы снять нагрузку выбираются каждый раз рандомно (защита от блокировки)
Отчеты по мероприятиям:
Быстрый  с пагинацией (с прокруткой списка)
В файле Excel (расширенная детализация)

Вход в админку:
Пользователь: admin
Пароль: admin

Сам тестовый бот: https://t.me/events_stand_bot
моя телега: @DeViking_ru 

p.s.
Кнопка Кабинет Администратора открыта на стенде всем. В рабочем режиме конечно только кому надо.
