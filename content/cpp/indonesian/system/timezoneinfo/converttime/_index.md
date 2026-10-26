---
title: ConvertTime()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengonversi waktu dari satu zona waktu ke zona waktu lain.
type: docs
weight: 40
url: /id/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) method

[Convert](../../convert/) waktu dari satu zona waktu ke zona waktu lain.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Source time zone. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Nilai Kembali

Converted date and time.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) method

[Convert](../../convert/) waktu ke waktu dalam zona waktu yang ditentukan.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Nilai Kembali

Converted date and time.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) method

[Convert](../../convert/) waktu ke waktu dalam zona waktu yang ditentukan.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Nilai Kembali

Converted date and time.

## Lihat Juga

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Kelas [DateTime](../../datetime/)
* Kelas [TimeZoneInfo](../)
* Kelas [DateTimeOffset](../../datetimeoffset/)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)