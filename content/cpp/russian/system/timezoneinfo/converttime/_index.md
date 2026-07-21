---
title: ConvertTime()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует время из одного часового пояса в другой.
type: docs
weight: 40
url: /ru/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr&, const TimeZoneInfoPtr&) метод


[Convert](../../convert/) время из одного часового пояса в другой.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Дата и время для преобразования. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Исходный часовой пояс. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Целевой часовой пояс. |

### Возвращаемое значение

Преобразованные дата и время.

## TimeZoneInfo::ConvertTime(const DateTimeOffset&, const TimeZoneInfoPtr&) метод


[Convert](../../convert/) время в указанном часовом поясе.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)& | Дата и время для преобразования. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Целевой часовой пояс. |

### Возвращаемое значение

Преобразованные дата и время.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr&) метод


[Convert](../../convert/) время в указанном часовом поясе.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Дата и время для преобразования. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Целевой часовой пояс. |

### Возвращаемое значение

Преобразованные дата и время.

## Смотрите также

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Класс [DateTime](../../datetime/)
* Класс [TimeZoneInfo](../)
* Класс [DateTimeOffset](../../datetimeoffset/)
* Пространство имен [System](../../)
* Library [Aspose.Slides](../../../)