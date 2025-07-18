# ** Анализ оттока клиентов Telco (Telco Churn Analysis)**

## **Про отток клиентов (Customer Churn)**

Ух, он ушел...

**Отток клиентов** - показатель того, что существующие клиенты перестают иметь дело с компанией.
Существует два вида оттока клиентов:
- Неизбежный отток
  Он происходит, когда клиенты прекращают взаимодействовать с компанией по независящим от них причинам.
- Предотвратимый поток
  Такой отток происходит в следствие того, что клиенты добровольно решают прекратить использование продуктов компании.

Второй вид оттока самый нежелательный, так как клиент, осознанно ушедший из компании, явно не был удовлетворен продуктом или сервисом компании.

Причины возникновения предотвратимого оттока:
- плохое обслуживание
- вопросы к ценообразованию
- проблемы с техподдержкой
- сложный продукт
- риски с безопасностью и конфиденциальностью
- отсутствие индивидуальных планов и пакетов
- трудности с оплатой
- более привлекательные условия у конкурента

Соответственно, сокращение оттока клиентов - одно из ключевых направлений бизнеса.

## **О компании**

Telco - фиктивная калифорнийская компания, предоставляющая услуги в сфере телекоммуникаций.
В частности, она предоставляет услуги по:
- голосовым звонкам
- интернету
- передаче данных

Данные о клиентах включают следующую информацию:
- Услуги/сервисы, которые подключил клиент (звонки, поддержка нескольких линий звонков, интернет, защита в сети, облачная резервная копия, защита устройства, техподдержка, телевидение, фильмы)
- Клиенты (количество времени в компании, тип контракта, способ оплаты, безналичный расчет, ежемесячные сборы, всего потрачено)
- Демография (пол, возраст, семейный статус, наличие детей)
- Отток (ушел клиент или нет)

## Шаги исследования

В ходе проекта я ответил на следующие вопросы:
1) Какая общая динамика оттока клиентов
2) 