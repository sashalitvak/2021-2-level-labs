# Лабораторные работы для 2-го курса ФПЛ (2021/2022)

[![Coverage Status](https://coveralls.io/repos/github/fipl-hse/2021-2-level-labs/badge.svg?branch=main)](https://coveralls.io/github/fipl-hse/2021-2-level-labs?branch=main)

В рамках предмета 
["Программирование для лингвистов"](https://www.hse.ru/edu/courses/476645685) 
в НИУ ВШЭ - Нижний Новгород.

Преподаватели: 

* [Демидовский Александр Владимирович](https://www.hse.ru/staff/demidovs) - лектор
* Кащихин Андрей Николаевич - преподаватель практики
* Ураев Дмитрий Юрьевич - преподаватель практики
* Кузнецова Валерия Андреевна - преподаватель практики

План лабораторных работ:

1. [Детектирование языка текста на основе доли пересечения наиболее частотных слов](./lab_1/lab_1.md)
   1. Дедлайн: 1 октября 
2. [Детектирование языка текста на основе расчёта расстояния между векторными представлениями текстов](./lab_2/lab_2.md)
   1. Дедлайн: 22 октября
3. TBD
4. TBD

## История занятий

|Дата|Тема лекции|Материалы практики|
|:--:|:---|:---|
|3.09.2021|Знакомство.|Как Python запускает программы? [Листинг кода](./seminars/09.03.2021/practice_1.py)|
|10.09.2021|Язык программирования Python. Историческая справка. Преимущества и недостатки языка. Виртуальная машина.|Что такое git? [Инструкции по настройке](./seminars/09.10.2021/practice_2.md)|
|17.09.2021| Типы данных. Числа. Введение в строки: строка - последовательность.| Числа. Срезы. [Листинг кода](./seminars/09.17.2021/practice_3.py)|
|24.09.2021| Строки как последовательности, штурм задачи про поиск вхождений строки| Строки. [Листинг кода](./seminars/09.24.2021/practice_4.py)|
|1.10.2021| Форматирование строк. Списки как последовательности. | Сдача лабораторной работы №1. |
|8.10.2021| Словари - изменяемые неупорядоченные отображения. | Списки. [Листинг кода](./seminars/10.08.2021/practice_6.py)|
|15.10.2021| Функции - способ организации и переиспользования кода. | Словари. [Листинг кода](./seminars/10.14.2021/practice_7.py)|
|29.10.2021| Области видимости: локальная, объемлющая, глобальная и встроенная. | Сдача лабораторной работы №2.|
|12.11.2021| Введение в ООП: общая мотивация, классы, метод `__init__`. | Практика создания классов. [Листинг кода](./seminars/11.12.2021/practice_8.py) |
|19.11.2021| Инкапсуляция, метод `__str__`. | Работа с классами и инкапсуляция атрибутов. [Листинг кода](./seminars/11.19.2021/practice_9.py) |
|26.11.2021| Наследование, особенности наследования атрибутов и методов. | Сдача лабораторной работы №3. |

## Литература

### Базовый уровень

1. Mark Lutz. 
   [Learning Python](https://www.amazon.com/Learning-Python-5th-Mark-Lutz/dp/1449355730).
2. Хирьянов Тимофей Фёдорович. Видеолекции. 
   [Практика программирования на Python 3](https://www.youtube.com/watch?v=fgf57Sa5A-A&list=PLRDzFCPr95fLuusPXwvOPgXzBL3ZTzybY).
3. Хирьянов Тимофей Фёдорович. Видеолекции. 
   [Алгоритмы и структуры данных на Python 3](https://www.youtube.com/watch?v=KdZ4HF1SrFs&list=PLRDzFCPr95fK7tr47883DFUbm4GeOjjc0).
4. [Official Python 3 documentation](https://docs.python.org/3/).

### Продвинутый уровень

1. Mark Lutz.
   [Programming Python: Powerful Object-Oriented Programming](https://www.amazon.com/Programming-Python-Powerful-Object-Oriented/dp/0596158106)
1. J. Burton Browning. 
   [Pro Python 3: Features and Tools for Professional Development](https://www.amazon.com/Pro-Python-Features-Professional-Development/dp/1484243846).

## Порядок сдачи и оценивания лабораторной работы

Порядок сдачи:

1. лабораторная работа допускается к очной сдаче.
2. студент объяснил работу программы и показал её в действии.
3. студент выполнил мини-задание ментора по некоторой модификации кода.
4. студент получает оценку:
   1. соответствующую ожидаемой, если все шаги выше выполнены и ментор удовлетворён ответом студента
   2. на балл выше ожидаемой, если все шаги выше выполнены и ментор решает поощрить студента за отличный ответ
   3. на балл ниже ожидаемой, если лабораторная работа сдаётся на неделю позже срока сдачи и выполнены критерии в 4.1
   4. на два балла ниже ожидаемой, если лабораторная работа сдаётся на две недели и позже от срока сдачи и выполнены критерии в 4.1

> Замечание: студент может улучшить оценку по лабораторной работе, если после основной сдачи выполнит 
> задания следующего уровня сложности
> относительно того уровня, на котором выполнялась реализация.

Лабораторная работа допускается к очной сдаче, если выполнены все пункты ниже:

1. представлена в виде пулл реквеста (Pull Request, PR) с правильно составленным названием по шаблону:
   `Laboratory work #<NUMBER>, <SURNAME> <NAME> - <UNIVERSITY GROUP NAME>`. Пример: `Laboratory work #1, Kuznetsova Valeriya - 20FPL1`.
2. имеет заполненный файл `target_score.txt` с ожидаемой оценкой. Допустимые значения: 4, 6, 8, 10.
3. имеет "зелёный" статус - автоматические проверки качества и стиля кода, соответствующие заданной ожидаемой оценке, удовлетворены.
4. имеет лейбл `done`, выставленный ментором. Означает, что ментор посмотрел код студента и удовлетворён качеством кода.

## Ресурсы

1. [Таблица успеваемости](https://docs.google.com/spreadsheets/d/1haOOmZQqzo9xykCbpeJ7uP1ZgO7N_Hsrhpb1apZtiDE/edit?usp=sharing)

## Запуск тестов

Для запуска тестов выполните следующую команду в папке с лабораторной работой:

```bash
python -m unittest discover -p "*_test.py" -s .
```

## Что делать если в родительском репозитории есть изменения и они мне нужны?

1. Создаем `upstream` таргет в репозитории:

```bash
git remote add upstream https://github.com/fipl-hse/2021-2-level-labs
```

2. Получаем данные об изменениях в удаленном репозитории:

```bash
git fetch upstream
```

3. Обновляем свой репозиторий с изменениями из удаленного репозитория:

```bash
git merge upstream/master
```


