---
title: GetLeapMonth()
second_title: Aspose.Slides для C++ справка API
description: Получает високосный месяц для указанного года.
type: docs
weight: 274
url: /ru/system.globalization/calendar/getleapmonth/
---
## Calendar::GetLeapMonth(int) const метод


Получает високосный месяц для указанного года.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, для которого нужно получить високосный месяц. |

### Возвращаемое значение

Високосный месяц указанного года или ноль, если в году нет високосного месяца.

## Calendar::GetLeapMonth(int, int) const метод


Получает високосный месяц для указанного года.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const =0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, для которого нужно получить високосный месяц. |
| era | int | Эра. |

### Возвращаемое значение

Високосный месяц указанного года указанной эры или ноль, если в году нет високосного месяца.

## См. также

* Класс [Calendar](../)
* Пространство имён [System::Globalization](../../)
* Библиотека [Aspose.Slides](../../../)