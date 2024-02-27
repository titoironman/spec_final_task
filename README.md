# Итоговая контрольная работа - Решение

## Информация о проекте
Необходимо организовать систему учета для питомника в котором живут домашние и вьючные животные.

## Как сдавать проект
Для сдачи проекта необходимо создать отдельный общедоступный репозиторий(Github, gitlub, или Bitbucket). Разработку вести в этом репозитории, использовать пул реквесты на изменения. Программа должна запускаться и работать, ошибок при выполнении программы быть не должно. Программа, может использоваться в различных системах, поэтому необходимо разработать класс в виде конструктора

### Задание / Решение

1.	Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного файла. Переименовать файл, дав ему новое имя (Друзья человека).

![image](https://github.com/titoironman/spec_final_task/assets/11056620/81423114-88a6-492b-bce6-dc4f652a7efc)

![image](https://github.com/titoironman/spec_final_task/assets/11056620/68690bae-4764-43dd-a38d-4eb34735704a)

![image](https://github.com/titoironman/spec_final_task/assets/11056620/a4165580-7cbb-445b-9bc8-72fd514cc34d)

![image](https://github.com/titoironman/spec_final_task/assets/11056620/386f8bd7-a8a2-46c2-86e1-61e55fcfa35f)

2.	Создать директорию, переместить файл туда.

![image](https://github.com/titoironman/spec_final_task/assets/11056620/157f559a-f8b0-4829-9411-f4e4cab276ff)

![image](https://github.com/titoironman/spec_final_task/assets/11056620/e5eeb6d5-d4a2-4995-8622-45eee6806ec2)

3.	Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.

![image](https://github.com/titoironman/spec_final_task/assets/11056620/450102d1-efbd-4eb7-aee5-a86978f21b00)

![image](https://github.com/titoironman/spec_final_task/assets/11056620/aea01d05-80ea-4853-b5e1-1872176f2c13)

4.	Установить и удалить deb-пакет с помощью dpkg.

![image](https://github.com/titoironman/spec_final_task/assets/11056620/18e19913-c7e2-4bd1-a951-40e0bddc01e8)

![image](https://github.com/titoironman/spec_final_task/assets/11056620/4b8317ce-7be9-4a9e-85d7-08e258bac3c6)

5.	Выложить историю команд в терминале ubuntu

    История [команд](https://github.com/titoironman/spec_final_task/blob/main/5.TaskHistoryList.md)

6.	Нарисовать диаграмму, в которой есть класс родительский класс, домашние животные и вьючные животные, в составы которых в случае домашних животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные войдут: Лошади, верблюды и ослы).

![image](https://github.com/titoironman/spec_final_task/assets/11056620/641102ad-661b-4c84-8e0a-508ae2ce4f83)

7.	В подключенном MySQL репозитории создать базу данных “Друзья человека”.

![image](https://github.com/titoironman/spec_final_task/assets/11056620/fc4bfcd2-2a1e-4185-8b91-be4256d9b53c)

8.	Создать таблицы с иерархией из диаграммы в БД.\

USE HumanFriends;

![image](https://github.com/titoironman/spec_final_task/assets/11056620/b8feaa18-28ad-4160-85c9-621dd9fa9530)


![image](https://github.com/titoironman/spec_final_task/assets/11056620/670a310a-f58b-45e9-a446-0da52d8fdb47)


![image](https://github.com/titoironman/spec_final_task/assets/11056620/aeab5cb3-df05-4d91-9060-a33cbe46a0ff)


![image](https://github.com/titoironman/spec_final_task/assets/11056620/f689eea5-7331-49c3-8c8b-896740e727bf)


![image](https://github.com/titoironman/spec_final_task/assets/11056620/0664b053-5934-45c6-82f3-acec0ba97335)


![image](https://github.com/titoironman/spec_final_task/assets/11056620/1a7c29ec-e66c-4ef7-bc2e-db529edf1a28)


![image](https://github.com/titoironman/spec_final_task/assets/11056620/235d5139-51fe-441a-af8a-ab2de2a3b8fb)


![image](https://github.com/titoironman/spec_final_task/assets/11056620/a6bb85fc-0ccd-45ad-901d-7a9be24478af)


![image](https://github.com/titoironman/spec_final_task/assets/11056620/783d8a7e-a867-4478-8c86-6f5e6710613e)


![image](https://github.com/titoironman/spec_final_task/assets/11056620/ff0007dd-901d-47b7-8c71-d727dc739711)


![image](https://github.com/titoironman/spec_final_task/assets/11056620/def79a03-c0a1-45e5-aee8-23eb13adb171)


![image](https://github.com/titoironman/spec_final_task/assets/11056620/a37848f7-75a4-458d-8eb4-8ffc0cbd07d1)


10.	Заполнить низкоуровневые таблицы именами(животных), командами которые они выполняют и датами рождения.
11.	Удалив из таблицы верблюдов, т.к. верблюдов решили перевезти в другой питомник на зимовку. Объединить таблицы лошади, и ослы в одну таблицу.
12.	Создать новую таблицу “молодые животные” в которую попадут все животные старше 1 года, но младше 3 лет и в отдельном столбце с точностью до месяца подсчитать возраст животных в новой таблице.
13.	Объединить все таблицы в одну, при этом сохраняя поля, указывающие на прошлую принадлежность к старым таблицам.
14.	Создать класс с Инкапсуляцией методов и наследованием по диаграмме.
15.	Написать программу, имитирующую работу реестра домашних животных.

В программе должен быть реализован следующий функционал:

14.1	Завести новое животное

14.2	определять животное в правильный класс

14.3	увидеть список команд, которое выполняет животное

14.4	обучить животное новым командам

14.5	Реализовать навигацию по меню

15.	Создайте класс Счетчик, у которого есть метод add(), увеличивающий̆ значение внутренней̆ int переменной̆ на 1 при нажатие “Завести новое животное” Сделайте так, чтобы с объектом такого типа можно было работать в блоке try-with-resources. Нужно бросить исключение, если работа с объектом типа счетчик была не в ресурсном try и/или ресурс остался открыт. Значение считать в ресурсе try, если при заведения животного заполнены все поля.
