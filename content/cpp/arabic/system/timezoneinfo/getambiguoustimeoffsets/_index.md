---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides لمرجع API C++
description: يحصل على تواريخ وأوقات UTC التي يمكن تعيين تاريخ ووقت محدد إليها.
type: docs
weight: 261
url: /ar/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const طريقة

يحصل على تواريخ وأوقات UTC التي يمكن تعيين تاريخ ووقت محدد إليها.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | التاريخ والوقت. |

### قيمة الإرجاع

[Array](../../array/) من تواريخ وأوقات UTC.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const طريقة

يحصل على تواريخ وأوقات UTC التي يمكن تعيين تاريخ ووقت محدد إليها.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | التاريخ والوقت. |

### قيمة الإرجاع

[Array](../../array/) من تواريخ وأوقات UTC.

## انظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* الفئة [TimeSpan](../../timespan/)
* الفئة [DateTime](../../datetime/)
* الفئة [TimeZoneInfo](../)
* الفئة [DateTimeOffset](../../datetimeoffset/)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)