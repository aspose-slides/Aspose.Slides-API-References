---
title: GetLeapMonth()
second_title: Aspose.Slides для C++ API Reference
description: Возвращает високосный месяц для указанного года.
type: docs
weight: 118
url: /ru/system.globalization/juliancalendar/getleapmonth/
---
## JulianCalendar::GetLeapMonth(int, int) const метод

Возвращает високосный месяц для указанного года.

```cpp
int System::Globalization::JulianCalendar::GetLeapMonth(int year, int era) const override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, в котором необходимо получить високосный месяц. |
| era | int | Эра. |

### Возвращаемое значение

Високосный месяц указанного года указанной эры или ноль, если в году нет високосного месяца.

## JulianCalendar::GetLeapMonth(int) const метод

Возвращает високосный месяц для указанного года.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, в котором необходимо получить високосный месяц. |

### Возвращаемое значение

Високосный месяц указанного года или ноль, если в году нет високосного месяца.

## JulianCalendar::GetLeapMonth(int, int) const метод

Возвращает високосный месяц для указанного года.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, в котором необходимо получить високосный месяц. |
| era | int | Эра. |

### Возвращаемое значение

Високосный месяц указанного года указанной эры или ноль, если в году нет високосного месяца.

## См. также

* Класс [JulianCalendar](../)
* Пространство имен [System::Globalization](../../)
* Библиотека [Aspose.Slides](../../../)