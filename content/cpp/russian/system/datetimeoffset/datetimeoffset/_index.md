---
title: DateTimeOffset()
second_title: Aspose.Slides для C++ справочник API
description: Конструктор по умолчанию.
type: docs
weight: 1
url: /ru/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() конструктор

Конструктор по умолчанию.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) конструктор

Конструктор.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Дата и время. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) конструктор

Конструктор.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ticks | **int64_t** | Количество тиков. |
| offset | [TimeSpan](../../timespan/) | Временной сдвиг от UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) конструктор

Конструктор.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Дата и время. |
| offset | [TimeSpan](../../timespan/) | Временной сдвиг от UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) конструктор

Конструктор.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год (от 1 до 9999). |
| month | int | Месяц (от 1 до 12). |
| day | int | День (от 1 до количества дней в месяце). |
| hour | int | Час (от 0 до 23). |
| minute | int | Минута (от 0 до 59). |
| second | int | Секунда (от 0 до 59). |
| offset | [TimeSpan](../../timespan/) | Временной сдвиг от UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) конструктор

Конструктор.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год (от 1 до 9999). |
| month | int | Месяц (от 1 до 12). |
| day | int | День (от 1 до количества дней в месяце). |
| hour | int | Час (от 0 до 23). |
| minute | int | Минута (от 0 до 59). |
| second | int | Секунда (от 0 до 59). |
| millisecond | int | Миллисекунда (от 0 до 999). |
| offset | [TimeSpan](../../timespan/) | Временной сдвиг от UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) конструктор

Конструктор.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год. |
| month | int | Месяц (от 1 до 12). |
| day | int | День (от 1 до количества дней в месяце). |
| hour | int | Час (от 0 до 23). |
| minute | int | Минута (от 0 до 59). |
| second | int | Секунда (от 0 до 59). |
| millisecond | int | Миллисекунда (от 0 до 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Календарь, используемый для интерпретации года, месяца и дня. |
| offset | [TimeSpan](../../timespan/) | Временной сдвиг от UTC. |

## См. также

* Тип [SharedPtr](../../sharedptr/)
* Класс [DateTimeOffset](../)
* Класс [DateTime](../../datetime/)
* Класс [TimeSpan](../../timespan/)
* Класс [Calendar](../../../system.globalization/calendar/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)