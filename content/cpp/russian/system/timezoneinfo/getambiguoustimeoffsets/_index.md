---
title: GetAmbiguousTimeOffsets()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает даты и времена UTC, к которым может быть сопоставлена указанная дата и время.
type: docs
weight: 261
url: /ru/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const метод

Получает даты и времена UTC, к которым может быть сопоставлена указанная дата и время.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Дата и время. |

### Возвращаемое значение

[Array](../../array/) дат и времени UTC.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const метод

Получает даты и времена UTC, к которым может быть сопоставлена указанная дата и время.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Дата и время. |

### Возвращаемое значение

[Array](../../array/) дат и времени UTC.

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [TimeSpan](../../timespan/)
* Класс [DateTime](../../datetime/)
* Класс [TimeZoneInfo](../)
* Класс [DateTimeOffset](../../datetimeoffset/)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)