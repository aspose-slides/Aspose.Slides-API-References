---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja az UTC dátumokat és időpontokat, amelyekre egy megadott dátum és idő leképezhető.
type: docs
weight: 261
url: /hu/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const metódus


Visszaadja az UTC dátumokat és időpontokat, amelyekre a megadott dátum és idő leképezhető.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Dátum és idő. |

### Visszatérési érték

[Array](../../array/) of UTC dates and times.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const metódus


Visszaadja az UTC dátumokat és időpontokat, amelyekre a megadott dátum és idő leképezhető.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Dátum és idő. |

### Visszatérési érték

[Array](../../array/) of UTC dates and times.

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [TimeSpan](../../timespan/)
* Osztály [DateTime](../../datetime/)
* Osztály [TimeZoneInfo](../)
* Osztály [DateTimeOffset](../../datetimeoffset/)
* Névtere [System](../../)
* Library [Aspose.Slides](../../../)