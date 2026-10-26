---
title: WaitOne()
second_title: Aspose.Slides για C++ Αναφορά API
description: Κλειδώνει το semaphore. Εκτελεί απεριόριστη αναμονή εάν είναι απαραίτητη.
type: docs
weight: 40
url: /el/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() μέθοδος


Κλειδώνει το semaphore. Εκτελεί απεριόριστη αναμονή εάν είναι απαραίτητο.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### Τιμή Επιστροφής

Πάντα επιστρέφει true καθώς δεν επιστρέφει μέχρι το semaphore να κλειδωθεί.

## Semaphore::WaitOne(int) μέθοδος


Κλειδώνει το semaphore. Εκτελεί αναμονή εάν είναι απαραίτητο.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| millisecondsTimeout | int | Χρονικό όριο αναμονής σε χιλιοστά του δευτερολέπτου. |

### Τιμή Επιστροφής

Επιστρέφει true εάν το semaphore κλειδώθηκε ή false εάν υπερβήθηκε το χρονικό όριο.

## Δείτε επίσης

* Κλάση [Semaphore](../)
* Χώρος Ονομάτων [System::Threading](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)