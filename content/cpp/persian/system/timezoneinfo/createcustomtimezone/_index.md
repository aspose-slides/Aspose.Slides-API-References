---
title: CreateCustomTimeZone()
second_title: Aspose.Slides برای C++ مرجع API
description: یک منطقهٔ زمانی سفارشی ایجاد می‌کند.
type: docs
weight: 105
url: /fa/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String&, TimeSpan, const String&, const String&, const String&, const ArrayPtr<AdjustmentRulePtr>&, bool) متد

یک منطقهٔ زمانی سفارشی ایجاد می‌کند.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | const [String](../../string/)& | شناسهٔ منطقهٔ زمانی. |
| base_utc_offset | [TimeSpan](../../timespan/) | فاصلهٔ زمانی بین زمان استاندارد منطقهٔ زمانی فعلی و زمان UTC. |
| display_name | const [String](../../string/)& | نام نمایشی. |
| standard_display_name | const [String](../../string/)& | نام زمان استاندارد. |
| daylight_display_name | const [String](../../string/)& | نام زمان صرفه‌جویی در نور روز. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)<[AdjustmentRulePtr](../adjustmentruleptr/)>& | [Array](../../array/) از قوانین تنظیم. |
| disable_daylight_saving_time | **bool** | True برای حذف هر اطلاعات صرفه‌جویی در نور روز موجود در adjustment_rules. |

### مقدار بازگشت

منطقهٔ زمانی جدید.

## TimeZoneInfo::CreateCustomTimeZone(const String&, TimeSpan, const String&, const String&, const String&, const ArrayPtr<AdjustmentRulePtr>&) متد

یک منطقهٔ زمانی سفارشی ایجاد می‌کند.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | const [String](../../string/)& | شناسهٔ منطقهٔ زمانی. |
| base_utc_offset | [TimeSpan](../../timespan/) | فاصلهٔ زمانی بین زمان استاندارد منطقهٔ زمانی فعلی و زمان UTC. |
| display_name | const [String](../../string/)& | نام نمایشی. |
| standard_display_name | const [String](../../string/)& | نام زمان استاندارد. |
| daylight_display_name | const [String](../../string/)& | نام زمان صرفه‌جویی در نور روز. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)<[AdjustmentRulePtr](../adjustmentruleptr/)>& | [Array](../../array/) از قوانین تنظیم. |

### مقدار بازگشت

منطقهٔ زمانی جدید.

## TimeZoneInfo::CreateCustomTimeZone(const String&, TimeSpan, const String&, const String&) متد

یک منطقهٔ زمانی سفارشی ایجاد می‌کند.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | const [String](../../string/)& | شناسهٔ منطقهٔ زمانی. |
| base_utc_offset | [TimeSpan](../../timespan/) | فاصلهٔ زمانی بین زمان استاندارد منطقهٔ زمانی فعلی و زمان UTC. |
| display_name | const [String](../../string/)& | نام نمایشی. |
| standard_display_name | const [String](../../string/)& | نام زمان استاندارد. |

### مقدار بازگشت

منطقهٔ زمانی جدید.

## همچنین ببینید

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* کلاس [String](../../string/)
* کلاس [TimeSpan](../../timespan/)
* کلاس [TimeZoneInfo](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)