---
title: ConvertTime()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงเวลาจากเขตเวลาเดียวไปยังอีกเขตเวลา
type: docs
weight: 40
url: /th/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) method


[Convert](../../convert/) เวลา จากเขตเวลาหนึ่งไปยังอีกเขตเวลา.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | วันที่และเวลาที่ต้องการแปลง. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | เขตเวลาต้นทาง. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | เขตเวลาเป้าหมาย. |

### ค่าที่ส่งกลับ

Converted date and time.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) method


[Convert](../../convert/) เวลา ไปยังเวลาในเขตเวลาที่ระบุ.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | วันที่และเวลาที่ต้องการแปลง. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | เขตเวลาเป้าหมาย. |

### ค่าที่ส่งกลับ

Converted date and time.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) method


[Convert](../../convert/) เวลา ไปยังเวลาในเขตเวลาที่ระบุ.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | วันที่และเวลาที่ต้องการแปลง. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | เขตเวลาเป้าหมาย. |

### ค่าที่ส่งกลับ

Converted date and time.

## ดูเพิ่มเติม

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [DateTime](../../datetime/)
* Class [TimeZoneInfo](../)
* Class [DateTimeOffset](../../datetimeoffset/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)