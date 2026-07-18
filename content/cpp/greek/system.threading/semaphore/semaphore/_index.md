---
title: Semaphore()
second_title: Aspose.Slides για την αναφορά API C++
description: Δημιουργεί ανώνυμο semaphore.
type: docs
weight: 1
url: /el/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) κατασκευαστής


Δημιουργεί ανώνυμο semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| initialCount | int | Αρχικός αριθμός ενεργών καταχωρήσεων. |
| maximumCount | int | Μέγιστος επιτρεπόμενος αριθμός καταχωρήσεων. |

## Semaphore::Semaphore(int, int, const String\&) κατασκευαστής


Δημιουργεί ονομασμένο semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| initialCount | int | Αρχικός αριθμός ενεργών καταχωρήσεων. |
| maximumCount | int | Μέγιστος επιτρεπόμενος αριθμός καταχωρήσεων. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) όνομα. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) κατασκευαστής


Δημιουργεί ονομασμένο semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| initialCount | int | Αρχικός αριθμός ενεργών καταχωρήσεων. |
| maximumCount | int | Μέγιστος επιτρεπόμενος αριθμός καταχωρήσεων. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) όνομα. |
| createdNew | **bool**\& | Αναφορά σε μεταβλητή που ορίζεται σε true εάν το semaphore δημιουργήθηκε και σε false εάν χρησιμοποιήθηκε υπάρχον semaphore με το ίδιο όνομα |

## Δείτε επίσης

* Κλάση [Semaphore](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Threading](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)