# customer-retention-in-the-online-store
# **Описание проекта**


Интернет-магазин «В один клик» продаёт разные товары: для детей, для дома, мелкую бытовую технику, косметику и даже продукты. Отчёт магазина за прошлый период показал, что активность покупателей начала снижаться. Привлекать новых клиентов уже не так эффективно: о магазине и так знает большая часть целевой аудитории. Возможный выход — удерживать активность постоянных клиентов. Сделать это можно с помощью персонализированных предложений.

# **Цель**

Разработать решение, которое позволит интернет-магазину «В один клик» персонализировать предложения для постоянных клиентов и увеличить их покупательскую активность.

# **Задачи**


## Классификация покупателей по уровню финансовой активности

* Проанализировать данные о покупках и разделить клиентов на две группы:
 + «Снизилась»: если клиент стал покупать меньше товаров.
 + «Прежний уровень»: если уровень покупательской активности остался прежним.

## Сбор и группировка данных о клиентах

* Коммуникация с клиентом: информация о взаимодействии клиента с сотрудниками компании (звонки, письма, обращения в поддержку).
* Продуктовое поведение: данные о том, какие товары покупает клиент, как часто, на какую сумму и т. д.
* Покупательское поведение: информация о покупках клиента в целом: сколько всего потратил, как часто оформляет заказы, использует ли скидки и промокоды.
* Поведение на сайте: данные о том, как клиент ведет себя на сайте: сколько времени проводит, сколько страниц просматривает, какие товары ищет.

## Визуализация данных

* Использовать диаграмму Исикавы (рыбья кость) для наглядного представления групп признаков и их влияния на целевой признак (уровень покупательской активности).
![image.png](attachment:image.png)

## Построение прогнозной модели

* Разработать модель машинного обучения, которая будет предсказывать вероятность снижения покупательской активности клиента в следующие три месяца на основе собранных данных.

## Включение данных о прибыльности

* Обогатить данные информацией о прибыльности каждого клиента за последние три месяца, полученной от финансового департамента.

## Сегментация клиентов и разработка рекомендаций

* Используя прогнозы модели и данные о прибыльности, разделить клиентов на сегменты.
* Разработать персонализированные предложения для каждого сегмента, направленные на увеличение их покупательской активности.
