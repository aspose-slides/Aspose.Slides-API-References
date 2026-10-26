---
title: operator-()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает новый экземпляр класса DateTimeOffset, представляющий значение даты и времени, которое является результатом вычитания указанного временного интервала из значения, представленного текущим объектом.
type: docs
weight: 521
url: /ru/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const method

Возвращает новый экземпляр класса [DateTimeOffset](../), представляющий значение даты и времени, которое является результатом вычитания указанного интервала времени из значения, представленного текущим объектом.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Интервал времени для вычитания |

### Возвращаемое значение

Новый экземпляр класса [DateTimeOffset](../), представляющий значение даты и времени, которое является результатом вычитания **value** из значения, представленного текущим объектом.

## DateTimeOffset::operator-(const DateTimeOffset\&) const method

Возвращает экземпляр класса [TimeSpan](../../timespan/), представляющий интервал времени между значениями даты и времени, представленными текущим объектом и указанным объектом.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Экземпляр класса [DateTime](../../datetime/), обозначающий один конец вычисляемого интервала |

### Возвращаемое значение

Экземпляр класса [TimeSpan](../../timespan/), представляющий интервал времени между значениями даты и времени, представленными текущим объектом и **other**.

## См. также

* Класс [DateTimeOffset](../)
* Класс [TimeSpan](../../timespan/)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)