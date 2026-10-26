---
title: Delay()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Δημιουργεί μια εργασία που ολοκληρώνεται μετά από καθυστέρηση χρόνου.
type: docs
weight: 105
url: /el/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) συνάρτηση


Δημιουργεί μια εργασία που ολοκληρώνεται μετά από καθυστέρηση χρόνου.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Ο αριθμός των χιλιοστών του δευτερολέπτου που πρέπει να περιμένει πριν ολοκληρώσει την επιστρεφόμενη εργασία, ή -1 για ατέρμονη αναμονή. |

### Τιμή επιστροφής

Μια εργασία που αντιπροσωπεύει την καθυστέρηση χρόνου.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) συνάρτηση


Δημιουργεί μια εργασία που ολοκληρώνεται μετά από καθυστέρηση χρόνου και μπορεί να ακυρωθεί.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Ο αριθμός των χιλιοστών του δευτερολέπτου που πρέπει να περιμένει πριν ολοκληρώσει την επιστρεφόμενη εργασία, ή -1 για ατέρμονη αναμονή. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Το διακριτικό ακύρωσης που μπορεί να χρησιμοποιηθεί για την ακύρωση της καθυστέρησης. |

### Τιμή επιστροφής

Μια εργασία που αντιπροσωπεύει την καθυστέρηση χρόνου.

## Δείτε επίσης

* Typedef [TaskPtr](../../system/taskptr/)
* Κλάση [CancellationToken](../../system.threading/cancellationtoken/)
* Χώρος ονομάτων [System::Threading::Tasks](../)
* Βιβλιοθήκη [Aspose.Slides](../../)