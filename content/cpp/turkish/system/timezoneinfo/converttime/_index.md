---
title: ConvertTime()
second_title: Aspose.Slides for C++ API Referansı
description: Zamanı bir saat diliminden diğerine dönüştürür.
type: docs
weight: 40
url: /tr/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) method

[Convert](../../convert/) bir saat diliminden diğerine zaman dönüştürür.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Dönüştürülecek tarih ve saat. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Kaynak saat dilimi. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Hedef saat dilimi. |

### Dönüş Değeri

Dönüştürülmüş tarih ve saat.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) method

[Convert](../../convert/) belirtilen bir saat dilimindeki zamana dönüştürür.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Dönüştürülecek tarih ve saat. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Hedef saat dilimi. |

### Dönüş Değeri

Dönüştürülmüş tarih ve saat.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) method

[Convert](../../convert/) belirtilen bir saat dilimindeki zamana dönüştürür.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Dönüştürülecek tarih ve saat. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Hedef saat dilimi. |

### Dönüş Değeri

Dönüştürülmüş tarih ve saat.

## Ayrıca Bakınız

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [DateTime](../../datetime/)
* Class [TimeZoneInfo](../)
* Class [DateTimeOffset](../../datetimeoffset/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)