# Домашнее задание по теме "Основы FastAPI и маршрутизация"

Цель: научиться создавать базовую маршрутизацию для обработки данных в
FastAPI.

## Задача "Начало пути":

Подготовка:

Установите фреймворк FastAPI при помощи пакетного менеджера pip. Версию
Python можете выбрать самостоятельно (3.9 - 3.12).

Маршрутизация:
1. Создайте приложение (объект) ```FastAPI``` предварительно импортировав
   класс для него.
2. Создайте маршрут к главной странице - "```/```". По нему должно выводиться
   сообщение "```Главная страница```".
3. Создайте маршрут к странице администратора - "```/user/admin```". По нему
   должно выводиться сообщение "```Вы вошли как администратор```".
4. Создайте маршрут к страницам пользователей используя параметр в пути -
   "```/user/{user_id}```". По нему должно выводиться сообщение "```Вы вошли
   как пользователь № <user_id>```".
5. Создайте маршрут к страницам пользователей, передавая данные в адресной
   строке - "```/user```". По нему должно выводиться сообщение "```Информация о
   пользователе. Имя: <username>, Возраст: <age>```".

Пример получившегося интерфейса Swagger:

![Swagger](https://static.tildacdn.com/tild3861-3835-4463-a139-373761316330/2024-07-22_17-48-46.png)

Примечания:
> 1. Все маршруты пишутся при мощи GET запроса.
> 2. Помните о важности порядка записи запросов в вашем файле.
> 3. Названия функций можете придумать самостоятельно с учётом логики
     прописанной в них.

Файл module_16_1.py загрузите на ваш GitHub репозиторий. В решении пришлите
ссылку на него.

Успехов!
