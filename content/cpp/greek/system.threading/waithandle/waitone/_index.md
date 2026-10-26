---
title: WaitOne()
second_title: Αναφορά API Aspose.Slides για C++
description: Περιμένει το χειριστήριο να ενεργοποιηθεί για απεριόριστη περίοδο.
type: docs
weight: 27
url: /el/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() μέθοδος

Αναμένει την εκκίνηση του χειριστηρίου για απεριόριστη περίοδο.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### Τιμή επιστροφής

Πάντα επιστρέφει true επειδή δεν συμβαίνει χρονικό όριο.

## WaitHandle::WaitOne(int) μέθοδος

Αναμένει την εκκίνηση του χειριστηρίου.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) για αναμονή, σε χιλιοστά του δευτερολέπτου· -1 σημαίνει απεριόριστη αναμονή, 0 σημαίνει έλεγχος-και-επιστροφή, θετικές τιμές είναι χρονικά όρια. |

### Τιμή επιστροφής

True εάν το χειριστήριο ενεργοποιηθεί, false εάν υπερβεί το χρονικό όριο.

## WaitHandle::WaitOne(TimeSpan) μέθοδος

Αναμένει την εκκίνηση του χειριστηρίου.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Ένα [System::TimeSpan](../../../system/timespan/) που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα [System::TimeSpan](../../../system/timespan/) που αντιπροσωπεύει -1 χιλιοστά του δευτερολέπτου για απεριόριστη αναμονή. |

### Τιμή επιστροφής

True εάν το χειριστήριο ενεργοποιηθεί, false εάν υπερβεί το χρονικό όριο.

## WaitHandle::WaitOne(int, bool) μέθοδος

Αναμένει την εκκίνηση του χειριστηρίου.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) για αναμονή, σε χιλιοστά του δευτερολέπτου· -1 σημαίνει απεριόριστη αναμονή, 0 σημαίνει έλεγχος-και-επιστροφή, θετικές τιμές είναι χρονικά όρια. |
| exitContext | **bool** | Αν είναι true, η αναμονή θα πρέπει να απελευθερώσει το κλείδωμα του χειριστηρίου πριν από την αναμονή. |

### Τιμή επιστροφής

True εάν το χειριστήριο ενεργοποιηθεί, false εάν υπερβεί το χρονικό όριο.

## Δείτε επίσης

* Κλάση [WaitHandle](../)
* Κλάση [TimeSpan](../../../system/timespan/)
* Χώρος ονομάτων [System::Threading](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)