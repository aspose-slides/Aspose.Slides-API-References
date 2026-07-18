---
title: WaitAny()
second_title: Aspose.Slides για C++ API Αναφορά
description: Περιμένει για να ενεργοποιηθεί οποιοδήποτε από τα handles.
type: docs
weight: 14
url: /el/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) μέθοδος

Περιμένει για οποιοδήποτε από τα handles να ενεργοποιηθεί.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\& | Handles για την αναμονή. |
| millisecondsTimeout | int | [Timeout](../../timeout/) για αναμονή, σε χιλιοστά του δευτερολέπτου· -1 σημαίνει απεριόριστη αναμονή, 0 σημαίνει έλεγχος-και-επιστροφή, οι θετικές τιμές είναι χρονικά όρια. |

### Τιμή Επιστροφής

Αληθές εάν ενεργοποιήθηκε οποιοδήποτε handle, ψευδές εάν ξεπέρασθηκε το χρονικό όριο.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) μέθοδος

Περιμένει για οποιοδήποτε από τα handles να ενεργοποιηθεί.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\& | Handles για την αναμονή. |
| timeout | [TimeSpan](../../../system/timespan/) | Ένα [System::TimeSpan](../../../system/timespan/) που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα [System::TimeSpan](../../../system/timespan/) που αντιπροσωπεύει -1 χιλιοστά του δευτερολέπτου για απεριόριστη αναμονή. |

### Τιμή Επιστροφής

Αληθές εάν ενεργοποιήθηκε οποιοδήποτε handle, ψευδές εάν ξεπέρασθηκε το χρονικό όριο.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) μέθοδος

Περιμένει για οποιοδήποτε από τα handles να ενεργοποιηθεί.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\& | Handles για την αναμονή. |

### Τιμή Επιστροφής

Αληθές όταν κάθε στοιχείο στο waitHandles έχει λάβει σήμα· διαφορετικά, η μέθοδος δεν επιστρέφει ποτέ.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)