---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει τις ημερομηνίες και ώρες UTC στις οποίες μπορεί να αντιστοιχηθεί μια καθορισμένη ημερομηνία και ώρα.
type: docs
weight: 261
url: /el/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const μέθοδος

Λαμβάνει τις ημερομηνίες και ώρες UTC στις οποίους μπορεί να αντιστοιχηθεί μια καθορισμένη ημερομηνία και ώρα.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Ημερομηνία και ώρα. |

### Τιμή Επιστροφής

[Array](../../array/) των ημερομηνιών και ωρών UTC.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const μέθοδος

Λαμβάνει τις ημερομηνίες και ώρες UTC στις οποίους μπορεί να αντιστοιχηθεί μια καθορισμένη ημερομηνία και ώρα.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Ημερομηνία και ώρα. |

### Τιμή Επιστροφής

[Array](../../array/) των ημερομηνιών και ωρών UTC.

## Δείτε επίσης

* Τύπος [ArrayPtr](../../arrayptr/)
* Κλάση [TimeSpan](../../timespan/)
* Κλάση [DateTime](../../datetime/)
* Κλάση [TimeZoneInfo](../)
* Κλάση [DateTimeOffset](../../datetimeoffset/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)