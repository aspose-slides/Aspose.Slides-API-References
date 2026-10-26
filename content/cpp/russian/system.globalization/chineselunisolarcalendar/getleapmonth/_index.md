---
title: GetLeapMonth()
second_title: Aspose.Slides для C++: справочник API
description: Возвращает високосный месяц для указанного года.
type: docs
weight: 92
url: /ru/system.globalization/chineselunisolarcalendar/getleapmonth/
---
## ChineseLunisolarCalendar::GetLeapMonth(int, int) const method

Получает високосный месяц для указанного года.

```cpp
int System::Globalization::ChineseLunisolarCalendar::GetLeapMonth(int year, int era) const override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, в котором нужно получить високосный месяц. |
| era | int | Эра. |

### Возвращаемое значение

Високосный месяц указанного года указанной эры или 0, если в этом году нет високосного месяца.

## ChineseLunisolarCalendar::GetLeapMonth(int) const method

Получает високосный месяц для указанного года.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, в котором нужно получить високосный месяц. |

### Возвращаемое значение

Високосный месяц указанного года или 0, если в этом году нет високосного месяца.

## ChineseLunisolarCalendar::GetLeapMonth(int, int) const method

Получает високосный месяц для указанного года.

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, в котором нужно получить високосный месяц. |
| era | int | Эра. |

### Возвращаемое значение

Високосный месяц указанного года указанной эры или 0, если в этом году нет високосного месяца.

## См. также

* Класс [ChineseLunisolarCalendar](../)
* Пространство имён [System::Globalization](../../)
* Библиотека [Aspose.Slides](../../../)