---
title: Timer()
second_title: Αναφορά API Aspose.Slides για C++
description: Κατασκευαστής.
type: docs
weight: 1
url: /el/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) constructor


Κατασκευαστής.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Συνάρτηση που θα κληθεί από το χρονόμετρο. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) constructor


Κατασκευαστής.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Συνάρτηση που θα κληθεί από το χρονόμετρο. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Όρισμα της συνάρτησης callback. |
| dueTime | **int64_t** | [Timeout](../../timeout/) πριν από την πρώτη κλήση της συνάρτησης callback, σε χιλιοστά του δευτερολέπτου· οι αρνητικές τιμές δεν προγραμματίζουν το χρονόμετρο μετά τη δημιουργία ώστε να μπορεί να προγραμματιστεί ξανά αργότερα. |
| period | **int64_t** | [Timeout](../../timeout/) μεταξύ των διαδοχικών κλήσεων της συνάρτησης callback, σε χιλιοστά του δευτερολέπτου· οι μη-θετικές τιμές σημαίνουν ότι το χρονόμετρο θα πρέπει να εκτελεστεί μόνο μία φορά. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) constructor


Κατασκευαστής.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Συνάρτηση που θα κληθεί από το χρονόμετρο. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Όρισμα της συνάρτησης callback. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) πριν από την πρώτη κλήση της συνάρτησης callback· οι αρνητικές τιμές δεν προγραμματίζουν το χρονόμετρο μετά τη δημιουργία ώστε να μπορεί να προγραμματιστεί ξανά αργότερα. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) μεταξύ των διαδοχικών κλήσεων της συνάρτησης callback· οι μη-θετικές τιμές σημαίνουν ότι το χρονόμετρο θα πρέπει να εκτελεστεί μόνο μία φορά. |

## See Also

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Timer](../)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)