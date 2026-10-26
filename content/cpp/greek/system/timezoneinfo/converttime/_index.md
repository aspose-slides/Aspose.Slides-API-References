---
title: ConvertTime()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει την ώρα από μία ζώνη ώρας σε άλλη.
type: docs
weight: 40
url: /el/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr&, const TimeZoneInfoPtr&) μέθοδος

[Convert](../../convert/) χρόνο από μια χρονική ζώνη σε άλλη.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Ημερομηνία και ώρα προς μετατροπή. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Πηγή χρονικής ζώνης. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Ζώνη ώρας προορισμού. |

### Τιμή επιστροφής

Ημερομηνία και ώρα που μετατράπηκε.

## TimeZoneInfo::ConvertTime(const DateTimeOffset&, const TimeZoneInfoPtr&) μέθοδος

[Convert](../../convert/) μετατρέπει το χρόνο στην ώρα μιας καθορισμένης ζώνης ώρας.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)& | Ημερομηνία και ώρα προς μετατροπή. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Ζώνη ώρας προορισμού. |

### Τιμή επιστροφής

Ημερομηνία και ώρα που μετατράπηκε.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr&) μέθοδος

[Convert](../../convert/) μετατρέπει το χρόνο στην ώρα μιας καθορισμένης ζώνης ώρας.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Ημερομηνία και ώρα προς μετατροπή. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)& | Ζώνη ώρας προορισμού. |

### Τιμή επιστροφής

Ημερομηνία και ώρα που μετατράπηκε.

## Δείτε επίσης

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Κλάση [DateTime](../../datetime/)
* Κλάση [TimeZoneInfo](../)
* Κλάση [DateTimeOffset](../../datetimeoffset/)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)