---
title: CreateCustomTimeZone()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้างโซนเวลาแบบกำหนดเอง
type: docs
weight: 105
url: /th/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method

สร้างโซนเวลาแบบกำหนดเอง

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | ตัวระบุโซนเวลา |
| base_utc_offset | [TimeSpan](../../timespan/) | ช่วงเวลาระหว่างเวลาแบบมาตรฐานของโซนเวลาปัจจุบันกับเวลา UTC |
| display_name | const [String](../../string/)\& | ชื่อที่แสดง |
| standard_display_name | const [String](../../string/)\& | ชื่อเวลามาตรฐาน |
| daylight_display_name | const [String](../../string/)\& | ชื่อเวลาออมแสง |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) ของกฎการปรับค่า |
| disable_daylight_saving_time | **bool** | จริงเพื่อละทิ้งข้อมูลเวลาออมแสงใด ๆ ที่อยู่ใน adjustment_rules |

### Return Value

โซนเวลาใหม่

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method

สร้างโซนเวลาแบบกำหนดเอง

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | ตัวระบุโซนเวลา |
| base_utc_offset | [TimeSpan](../../timespan/) | ช่วงเวลาระหว่างเวลาแบบมาตรฐานของโซนเวลาปัจจุบันกับเวลา UTC |
| display_name | const [String](../../string/)\& | ชื่อที่แสดง |
| standard_display_name | const [String](../../string/)\& | ชื่อเวลามาตรฐาน |
| daylight_display_name | const [String](../../string/)\& | ชื่อเวลาออมแสง |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) ของกฎการปรับค่า |

### Return Value

โซนเวลาใหม่

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method

สร้างโซนเวลาแบบกำหนดเอง

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | ตัวระบุโซนเวลา |
| base_utc_offset | [TimeSpan](../../timespan/) | ช่วงเวลาระหว่างเวลาแบบมาตรฐานของโซนเวลาปัจจุบันกับเวลา UTC |
| display_name | const [String](../../string/)\& | ชื่อที่แสดง |
| standard_display_name | const [String](../../string/)\& | ชื่อเวลามาตรฐาน |

### Return Value

โซนเวลาใหม่

## ดูเพิ่มเติม

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)