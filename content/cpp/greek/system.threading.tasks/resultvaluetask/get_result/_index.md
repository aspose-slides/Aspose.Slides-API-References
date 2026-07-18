---
title: get_Result()
second_title: Aspose.Slides για C++ αναφορά API
description: Αποκτά το αποτέλεσμα της ολοκληρωμένης εργασίας.
type: docs
weight: 66
url: /el/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() μέθοδος

Αποκτά το αποτέλεσμα της ολοκληρωμένης εργασίας.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### Τιμή Επιστροφής

T Η τιμή του αποτελέσματος.

## Παρατηρήσεις

Αν η εργασία υποστηρίζεται από ένα ResultTask<T>, αυτή η μέθοδος θα αναμένει το αποτέλεσμα και θα το αποθηκεύσει στην κρυφή μνήμη. Οι επόμενες κλήσεις θα επιστρέφουν την αποθηκευμένη τιμή χωρίς αναμονή.

## Δείτε επίσης

* Κλάση [ResultValueTask](../)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)