---
title: Join()
second_title: Aspose.Slides για C++ API Αναφορά
description: Συγχωνεύει το διαχειριζόμενο νήμα. Εκτελεί απεριόριστη αναμονή εάν απαιτείται.
type: docs
weight: 196
url: /el/system.threading/thread/join/
---
## Thread::Join() μέθοδος

Συγχωνεύει το διαχειριζόμενο νήμα. Εκτελεί απεριόριστη αναμονή εάν απαιτείται.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) μέθοδος

Συγχωνεύει το διαχειριζόμενο νήμα. Εκτελεί περιορισμένη αναμονή.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| millisecondsTimeout | int | Χρονικό όριο αναμονής σε χιλιοστά του δευτερολέπτου. |

### Τιμή Επιστροφής

True αν το νήμα ενώνεται επιτυχώς, false αν το χρονικό όριο υπερβεί.

## Thread::Join(TimeSpan) μέθοδος

Συγχωνεύει το διαχειριζόμενο νήμα. Εκτελεί περιορισμένη αναμονή.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Ένα [TimeSpan](../../../system/timespan/) ορισμένο στο χρονικό διάστημα για να περιμένει το νήμα να τερματιστεί. |

### Τιμή Επιστροφής

True αν το νήμα ενώνεται επιτυχώς, false αν το χρονικό όριο υπερβεί.

## Δείτε επίσης

* Κλάση [Thread](../)
* Κλάση [TimeSpan](../../../system/timespan/)
* Χώρος ονομάτων [System::Threading](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)