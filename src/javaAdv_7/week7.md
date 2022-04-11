## Week 7

###### HW links

7.1 https://docs.google.com/document/d/1Xvm1oIE13aM7zBnasfCyos6A5G_rwRZSWfBkASyueS0/edit

7.2 https://docs.google.com/document/d/125HrtnpYpR_quoqZn2Sk-ECIHrD_S6P58mT6s4a7qKQ/edit

###### Tasks:

**HW 7.1**

1) Необходимо создать класс Employee со следующими методами:
getBaseSalary - получить базовую ставку
setBaseSalary
getName - получить имя
setName
getSalary - получить зарплату
   

2) Необходимо создать класс Worker где метод getSalary будет возвращать базовую ставку.
Необходимо создать класс Manager в который нужно добавить следующие методы:
getNumberOfSubordinates - получить количество подчиненных
setNumberOfSubordinates в классе, метод getSalary будет возвращать значение по формуле - <базовая ставка> * (<количество подчиненных> / 100 * 3). Если количество подчиненных 0, то результат как у обычного рабочего.
Необходимо создать класс Director с теми же методами, что и Manager, но метод getSalary должен возвращать результат по формуле - <базовая ставка> * (<количество подчиненных> / 100 * 9). Если количество подчиненных 0, то результат как у обычного рабочего.


3) Необходимо создать утилитарный класс со следующими методами:

* поиск сотрудника в массиве по его имени
* поиск сотрудника в массиве по вхождению указанной строки в его имени
* подсчет зарплатного бюджета для всех сотрудников в массиве
* поиск наименьшей зарплаты в массиве
* поиск наибольшей зарплаты в массиве
* поиск наименьшего количества подчиненных в массиве менеджеров
* поиск наибольшего количества подчиненных в массиве менеджеров
* поиск наибольшей надбавки (разнице между базовой зарплатой и выплатой) в массиве менеджеров
* поиск наименьшей надбавки (разнице между базовой ставки и зарплатой) в массиве менеджеров


**HW 7.2**

_Задача №1_
Создать класс Month с полями: имя месяца, количеством дней и количеством рабочих дней. Создать класс MonthUtils который бы хранил подготовленные месяцы или их массивы для использования (объекты класса Month).


_Задача №2_ 
Необходимо создать класс Employee с полями: имя, возраст, пол и ЗП в день. Все поля сделать приватными и для каждого поля добавить методы set и get. Класс должен иметь метод - getSalary(Month[] monthArray), метод возвращает зарплату за те месяцы которые были переданы в качестве аргумента.


_Задача №3_ 
Необходимо создать класс Manager с полями: имя, возраст, пол, ЗП в день и количество подчиненных. Все поля сделать приватными и для каждого поля добавить методы set и get. Класс должен иметь метод - getSalary(Month[] monthArray), метод возвращает зарплату за те месяцы которые были переданы в качестве аргумента.
К рассчитанной ЗП должно прибавляться по 1% за каждого подчиненного.