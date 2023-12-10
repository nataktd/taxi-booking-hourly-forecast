# taxi-booking-hourly-forecast
# Описание проекта
В нашем распоряжении данные Компания «Чётенькое такси» о заказах такси в аэропортах.
Компания поставила перед собой задаче привлекать больше водителей в период пиковой нагрузки. Для этого нужно спрогнозировать количество заказов такси на следующий час.
# Цель:
Необходимо постройте модель для такого предсказания количество заказов такси в аэропортах на следующий час.
Значение метрики RMSE на тестовой выборке должно быть не больше 48.
# План работы:

1  Изучение данных и подготовка к работе

1.1  Методы и константы

1.2  Общая информация о датасете и данных.

1.3  Визуализация

1.4  Анализ статистических характеристик

1.5  Разложение временного ряда на компоненты.

1.6  Примечание. Стабилизация временного ряда

1.7  Примечание. Выбросы и аномалии

2  Подготовка данных и обучение моделей

2.1  Новые признаки

2.1.1  Корреляция признаков

2.1.1.1  Примечание. Автокорреляция

2.2  Подготовка выборок

3  Обучение алгоритмов

3.0.1  Примечание. Оценка важности признаков

3.1  Проверка лучшей модели на адекватность

3.2  Проверка лучшей модели на тестовой выборке

4  Итоги и выводы
# Итоги
На тестовой выборке результаты лучшей модели алгоритма машинного обучения Ridgeоказались лучше, чем требовалось в задаче (значение метрики RMSE должно быть меньше 48), значение RMSE - 45.31.