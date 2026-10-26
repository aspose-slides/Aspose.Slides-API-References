---
title: WaitOne()
second_title: Aspose.Slides για C++ API Αναφορά
description: Κλειδώνει το mutex. Εκτελεί απεριόριστη αναμονή εάν είναι απαραίτητο.
type: docs
weight: 53
url: /el/system.threading/mutex/waitone/
---
## Mutex::WaitOne() μέθοδος

Κλειδώνει το mutex. Εκτελεί απεριόριστη αναμονή εάν είναι απαραίτητο.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### Τιμή Επιστροφής

Επιστρέφει πάντα true καθώς δεν επιστρέφει μέχρι να κλειδ ωθεί το mutex.

## Mutex::WaitOne(int) μέθοδος

Κλειδώνει το mutex. Εκτελεί αναμονή εάν είναι απαραίτητο.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Χρονικό όριο αναμονής σε χιλιοστά του δευτερολέπτου. |

### Τιμή Επιστροφής

Επιστρέφει true εάν το mutex κλειδώθηκε ή false εάν ξεπέρασταν το χρονικό όριο.

## Mutex::WaitOne(TimeSpan) μέθοδος

Κλειδώνει το mutex. Εκτελεί αναμονή εάν είναι απαραίτητο.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Ένα [System::TimeSpan](../../../system/timespan/) που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα [System::TimeSpan](../../../system/timespan/) που αντιπροσωπεύει -1 χιλιοστά του δευτερολέπτου για απεριόριστη αναμονή. |

### Τιμή Επιστροφής

Επιστρέφει true εάν το mutex κλειδώθηκε ή false εάν ξεπέρασταν το χρονικό όριο.

## Δείτε επίσης

* Κλάση [Mutex](../)
* Κλάση [TimeSpan](../../../system/timespan/)
* Χώρος ονομάτων [System::Threading](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)