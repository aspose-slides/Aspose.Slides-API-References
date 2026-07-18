---
title: Change()
second_title: Αναφορά API Aspose.Slides για C++
description: Επαναπρογραμματίζει ή ακυρώνει το χρονοδιακόπτη.
type: docs
weight: 14
url: /el/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) μέθοδος


Επαναπρογραμματίζει ή ακυρώνει το χρονοδιακόπτη.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) πριν από την επόμενη κλήση της συνάρτησης ανάκλησης, σε χιλιοστά του δευτερολέπτου; οι αρνητικές τιμές ακυρώνουν το χρονοδιακόπτη ακόμη και αν είχε προγραμματιστεί. |
| period | **int64_t** | [Timeout](../../timeout/) μεταξύ διαδοχικών κλήσεων της συνάρτησης ανάκλησης, σε χιλιοστά του δευτερολέπτου; μη θετικές τιμές σημαίνουν ότι το χρονοδιακόπτη θα εκτελεστεί μόνο μία φορά. |

## Timer::Change(System::TimeSpan, System::TimeSpan) μέθοδος


Επαναπρογραμματίζει ή ακυρώνει το χρονοδιακόπτη.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) πριν από την επόμενη κλήση της συνάρτησης ανάκλησης· οι αρνητικές τιμές ακυρώνουν το χρονοδιακόπτη ακόμη και αν ήταν προγραμματισμένο. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) μεταξύ διαδοχικών κλήσεων της συνάρτησης ανάκλησης· μη θετικές τιμές σημαίνουν ότι το χρονοδιακόπτη θα εκτελεστεί μόνο μία φορά. |

## Δείτε επίσης

* Κλάση [Timer](../)
* Κλάση [TimeSpan](../../../system/timespan/)
* Χώρος ονομάτων [System::Threading](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)