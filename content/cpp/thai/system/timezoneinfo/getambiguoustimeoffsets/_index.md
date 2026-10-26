---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับค่าวันและเวลาตาม UTC ที่สามารถแมพจากวันที่และเวลาเฉพาะได้.
type: docs
weight: 261
url: /th/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const เมธอด

รับค่าวันและเวลาตาม UTC ที่สามารถแมพจากวันที่และเวลาเฉพาะได้

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time. |

### ค่าที่ส่งกลับ

[Array](../../array/) ของวันที่และเวลาตาม UTC.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const เมธอด

รับค่าวันและเวลาตาม UTC ที่สามารถแมพจากวันที่และเวลาเฉพาะได้

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date and time. |

### ค่าที่ส่งกลับ

[Array](../../array/) ของวันที่และเวลาตาม UTC.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Class [TimeSpan](../../timespan/)
* Class [DateTime](../../datetime/)
* Class [TimeZoneInfo](../)
* Class [DateTimeOffset](../../datetimeoffset/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)