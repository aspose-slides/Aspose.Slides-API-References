---
title: DateTimeOffset()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προεπιλεγμένος κατασκευαστής.
type: docs
weight: 1
url: /el/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() κατασκευαστής

Προεπιλεγμένος κατασκευαστής.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) κατασκευαστής

Κατασκευαστής.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Ημερομηνία και ώρα. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) κατασκευαστής

Κατασκευαστής.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ticks | **int64_t** | Αριθμός κρονοστοιχείων. |
| offset | [TimeSpan](../../timespan/) | Χρονική μετατόπιση από UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) κατασκευαστής

Κατασκευαστής.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Ημερομηνία και ώρα. |
| offset | [TimeSpan](../../timespan/) | Χρονική μετατόπιση από UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) κατασκευαστής

Κατασκευαστής.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| year | int | Έτος (1 έως 9999). |
| month | int | Μήνας (1 έως 12). |
| day | int | Ημέρα (1 έως τον αριθμό των ημερών του μήνα). |
| hour | int | Ώρα (0 έως 23). |
| minute | int | Λεπτό (0 έως 59). |
| second | int | Δευτερόλεπτο (0 έως 59). |
| offset | [TimeSpan](../../timespan/) | Χρονική μετατόπιση από UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) κατασκευαστής

Κατασκευαστής.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| year | int | Έτος (1 έως 9999). |
| month | int | Μήνας (1 έως 12). |
| day | int | Ημέρα (1 έως τον αριθμό των ημερών του μήνα). |
| hour | int | Ώρα (0 έως 23). |
| minute | int | Λεπτό (0 έως 59). |
| second | int | Δευτερόλεπτο (0 έως 59). |
| millisecond | int | Χιλιοστό του δευτερολέπτου (0 έως 999). |
| offset | [TimeSpan](../../timespan/) | Χρονική μετατόπιση από UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) κατασκευαστής

Κατασκευαστής.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| year | int | Έτος. |
| month | int | Μήνας (1 έως 12). |
| day | int | Ημέρα (1 έως τον αριθμό των ημερών του μήνα). |
| hour | int | Ώρα (0 έως 23). |
| minute | int | Λεπτό (0 έως 59). |
| second | int | Δευτερόλεπτο (0 έως 59). |
| millisecond | int | Χιλιοστό του δευτερολέπτου (0 έως 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Ημερολόγιο που χρησιμοποιείται για την ερμηνεία του έτους, του μήνα και της ημέρας. |
| offset | [TimeSpan](../../timespan/) | Χρονική μετατόπιση από UTC. |

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [DateTimeOffset](../)
* Κλάση [DateTime](../../datetime/)
* Κλάση [TimeSpan](../../timespan/)
* Κλάση [Calendar](../../../system.globalization/calendar/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)