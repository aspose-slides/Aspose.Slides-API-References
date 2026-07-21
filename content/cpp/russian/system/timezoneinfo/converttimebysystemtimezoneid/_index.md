---
title: ConvertTimeBySystemTimeZoneId()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует время в указанный часовой пояс.
type: docs
weight: 53
url: /ru/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String&) метод

[Convert](../../convert/) преобразует время в указанный часовой пояс.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Дата и время для преобразования. |
| destination_time_zone_id | const [String](../../string/)\& | Идентификатор целевого часового пояса. |

### Возвращаемое значение

Преобразованная дата и время.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset&, const String&) метод

[Convert](../../convert/) преобразует время в указанный часовой пояс.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Дата и время для преобразования. |
| destination_time_zone_id | const [String](../../string/)\& | Идентификатор целевого часового пояса. |

### Возвращаемое значение

Преобразованная дата и время.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String&, const String&) метод

[Convert](../../convert/) преобразует время в указанный часовой пояс.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Дата и время для преобразования. |
| source_time_zone_id | const [String](../../string/)\& | Идентификатор исходного часового пояса. |
| destination_time_zone_id | const [String](../../string/)\& | Идентификатор целевого часового пояса. |

### Возвращаемое значение

Преобразованная дата и время.

## См. также

* Класс [DateTime](../../datetime/)
* Класс [String](../../string/)
* Класс [TimeZoneInfo](../)
* Класс [DateTimeOffset](../../datetimeoffset/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)