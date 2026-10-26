---
title: FromException()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί μια εργασία που έχει ολοκληρωθεί με μια καθορισμένη εξαίρεση.
type: docs
weight: 131
url: /el/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) συνάρτηση


Δημιουργεί μια εργασία που έχει ολοκληρωθεί με μια καθορισμένη εξαίρεση.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Η εξαίρεση με την οποία θα ολοκληρωθεί η εργασία. |

### Τιμή Επιστροφής

Μια εργασία με σφάλμα.

## System::Threading::Tasks::FromException(const Exception\&) συνάρτηση


Δημιουργεί μια εργασία που έχει ολοκληρωθεί με μια καθορισμένη εξαίρεση και τύπο αποτελέσματος.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TResult | Ο τύπος του αποτελέσματος της εργασίας. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Η εξαίρεση με την οποία θα ολοκληρωθεί η εργασία. |

### Τιμή Επιστροφής

Μια εργασία με σφάλμα με τον καθορισμένο τύπο αποτελέσματος.

## Δείτε επίσης

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)