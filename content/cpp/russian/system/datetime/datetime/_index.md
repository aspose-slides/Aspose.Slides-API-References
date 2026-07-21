---
title: DateTime()
second_title: Aspose.Slides для C++: справочник API
description: Создает экземпляр, представляющий наименьшее возможное значение даты и времени, равное MinValue.
type: docs
weight: 1
url: /ru/system/datetime/datetime/
---
## DateTime::DateTime() конструктор

Создает экземпляр, представляющий наименьшее возможное значение даты и времени, равное MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) конструктор

Создает экземпляр, представляющий значение даты и времени, указанное конкретным годом, месяцем и днем.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, который будет представлен создаваемым экземпляром. |
| month | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| day | int | День **month**, который будет представлен создаваемым экземпляром. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) конструктор

Создает экземпляр, представляющий значение даты и времени, указанное конкретным годом, месяцем и днем в указанном календаре.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, который будет представлен создаваемым экземпляром. |
| month | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| day | int | День **month**, который будет представлен создаваемым экземпляром. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Календарь, используемый для интерпретации указанных **year**, **month** и **day**. |

## DateTime::DateTime(int, int, int, int, int, int) конструктор

Создает экземпляр, представляющий значение даты и времени, указанное конкретным годом, месяцем, днем, часом, минутой и секундой.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, который будет представлен создаваемым экземпляром. |
| month | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| day | int | День **month**, который будет представлен создаваемым экземпляром. |
| hour | int | Час **day**, который будет представлен создаваемым экземпляром. |
| minute | int | Минутa **hour**, которая будет представлена создаваемым экземпляром. |
| second | int | Секунда **minute**, которая будет представлена создаваемым экземпляром. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) конструктор

Создает экземпляр, представляющий значение даты и времени, указанное конкретным годом, месяцем, днем, часом, минутой и секундой.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, который будет представлен создаваемым экземпляром. |
| month | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| day | int | День **month**, который будет представлен создаваемым экземпляром. |
| hour | int | Час **day**, который будет представлен создаваемым экземпляром. |
| minute | int | Минутa **hour**, которая будет представлена создаваемым экземпляром. |
| second | int | Секунда **minute**, которая будет представлена создаваемым экземпляром. |
| kind | [DateTimeKind](../../datetimekind/) | Значение, указывающее, являются ли переданные параметры даты и времени локальным временем, временем UTC или ни тем, ни другим. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) конструктор

Создает экземпляр, представляющий значение даты и времени, указанное конкретным годом, месяцем, днем, часом, минутой и секундой в указанном календаре.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, который будет представлен создаваемым экземпляром. |
| month | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| day | int | День **month**, который будет представлен создаваемым экземпляром. |
| hour | int | Час **day**, который будет представлен создаваемым экземпляром. |
| minute | int | Минутa **hour**, которая будет представлена создаваемым экземпляром. |
| second | int | Секунда **minute**, которая будет представлена создаваемым экземпляром. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Календарь, используемый для интерпретации указанных **year**, **month** и **day**. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) конструктор

Создает экземпляр, представляющий значение даты и времени, указанное конкретным годом, месяцем, днем, часом, минутой, секундой и миллисекундой.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, который будет представлен создаваемым экземпляром. |
| month | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| day | int | День **month**, который будет представлен создаваемым экземпляром. |
| hour | int | Час **day**, который будет представлен создаваемым экземпляром. |
| minute | int | Минутa **hour**, которая будет представлена создаваемым экземпляром. |
| second | int | Секунда **minute**, которая будет представлена создаваемым экземпляром. |
| millisecond | int | Миллисекунда **second**, которая будет представлена создаваемым экземпляром. |
| kind | [DateTimeKind](../../datetimekind/) | Значение, указывающее, являются ли переданные параметры даты и времени локальным временем, временем UTC или ни тем, ни другим. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) конструктор

Создает экземпляр, представляющий значение даты и времени, указанное конкретным годом, месяцем, днем, часом, минутой, секундой и миллисекундой в указанном календаре.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год, который будет представлен создаваемым экземпляром. |
| month | int | Месяц **year**, который будет представлен создаваемым экземпляром. |
| day | int | День **month**, который будет представлен создаваемым экземпляром. |
| hour | int | Час **day**, который будет представлен создаваемым экземпляром. |
| minute | int | Минутa **hour**, которая будет представлена создаваемым экземпляром. |
| second | int | Секунда **minute**, которая будет представлена создаваемым экземпляром. |
| millisecond | int | Миллисекунда **second**, которая будет представлена создаваемым экземпляром. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Значение, указывающее, являются ли переданные параметры даты и времени локальным временем, временем UTC или ни тем, ни другим. |
| calendar | [DateTimeKind](../../datetimekind/) | Календарь, используемый для интерпретации указанных **year**, **month** и **day**. |

## DateTime::DateTime(int64_t, DateTimeKind) конструктор

Создает экземпляр, представляющий значение даты и времени, указанное числом тиков.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| ticks | **int64_t** | Количество интервалов по 100 нс, прошедших с 1 января 0001 г. 00:00:00.000 по григорианскому календарю. |
| kind | [DateTimeKind](../../datetimekind/) | Значение, указывающее, параметр **ticks** представляет локальное время, время UTC или ни тем, ни другим. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) конструктор

Создает экземпляр, представляющий значение даты и времени, указанное числом тиков. ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| ticks | **int64_t** | Количество интервалов по 100 нс, прошедших с 1 января 0001 г. 00:00:00.000 по григорианскому календарю. |
| kind | [DateTimeKind](../../datetimekind/) | Значение, указывающее, параметр **ticks** представляет локальное время, время UTC или ни тем, ни другим. |
| is_ambiguous_local_dst | **bool** | true, если указанная дата и время неоднозначны и могут соответствовать множеству UTC-времен. |

## DateTime::DateTime(const DateTime\&) конструктор

Копирующий конструктор экземпляра.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| dt | const [DateTime](../)\& | Экземпляр класса [DateTime](../), из которого копируется представляемое значение даты и времени. |

## Смотрите также

* Перечисление [DateTimeKind](../../datetimekind/)
* Тип [SharedPtr](../../sharedptr/)
* Класс [DateTime](../)
* Класс [Calendar](../../../system.globalization/calendar/)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)