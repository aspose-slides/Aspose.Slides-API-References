---
title: WaitAll()
second_title: Αναφορά API για C++ του Aspose.Slides
description: Περιμένει μέχρι όλες οι αναφορές να ενεργοποιηθούν.
type: docs
weight: 1
url: /el/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method


Περιμένει μέχρι όλοι οι αναφορές να ενεργοποιηθούν.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Αναφορές για τις οποίες περιμένει. |
| millisecondsTimeout | int | [Timeout](../../timeout/) για αναμονή, σε χιλιοστά του δευτερολέπτου· -1 σημαίνει απεριόριστη αναμονή, 0 σημαίνει έλεγχο-και-επιστροφή, θετικές τιμές είναι λήξη χρόνου. |

### Τιμή Επιστροφής

True αν όλες οι αναφορές ενεργοποιήθηκαν, false αν υπέρβασε το χρονικό όριο.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method


Περιμένει μέχρι όλοι οι αναφορές να ενεργοποιηθούν.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Αναφορές για τις οποίες περιμένει. |
| timeout | [TimeSpan](../../../system/timespan/) | Ένα [System::TimeSpan](../../../system/timespan/) που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα [System::TimeSpan](../../../system/timespan/) που αντιπροσωπεύει -1 χιλιοστά του δευτερολέπτου για απεριόριστη αναμονή. |

### Τιμή Επιστροφής

True αν όλες οι αναφορές ενεργοποιήθηκαν, false αν υπέρβασε το χρονικό όριο.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method


Περιμένει μέχρι όλοι οι αναφορές να ενεργοποιηθούν.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Αναφορές για τις οποίες περιμένει. |

### Τιμή Επιστροφής

True όταν κάθε στοιχείο στο waitHandles έχει λάβει σήμα· διαφορετικά η μέθοδος δεν επιστρέφει ποτέ.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [WaitHandle](../)
* Κλάση [TimeSpan](../../../system/timespan/)
* Χώρος ονομάτων [System::Threading](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)