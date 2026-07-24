---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen tarih ve zamanın eşlenebileceği UTC tarih ve zamanlarını alır.
type: docs
weight: 261
url: /tr/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const yöntemi

Belirtilen tarih ve zamanın eşlenebileceği UTC tarih ve zamanlarını alır.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Tarih ve saat. |

### Dönüş Değeri

[Array](../../array/) UTC tarih ve zamanları.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const yöntemi

Belirtilen tarih ve zamanın eşlenebileceği UTC tarih ve zamanlarını alır.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Tarih ve saat. |

### Dönüş Değeri

[Array](../../array/) UTC tarih ve zamanları.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [TimeSpan](../../timespan/)
* Sınıf [DateTime](../../datetime/)
* Sınıf [TimeZoneInfo](../)
* Sınıf [DateTimeOffset](../../datetimeoffset/)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)