---
title: AsTask()
second_title: Aspose.Slides για C++ API Reference
description: Μετατρέπει αυτό το ResultValueTask σε δείκτη κοινής χρήσης προς ResultTask<T>.
type: docs
weight: 79
url: /el/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const μέθοδος


Μετατρέπει αυτό το [ResultValueTask](../) σε έναν δείκτη κοινής χρήσης προς ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### Τιμή Επιστροφής

RTaskPtr<T> Ένας δείκτης κοινής χρήσης προς ResultTask<T> που αντιπροσωπεύει αυτήν τη λειτουργία.
## Παρατηρήσεις



Αν το [ResultValueTask](../) περιέχει άμεσο αποτέλεσμα, δημιουργεί μια ολοκληρωμένη εργασία με αυτό το αποτέλεσμα. Αν περιέχει εργασία, επιστρέφει έναν δείκτη κοινής χρήσης προς αυτήν την εργασία. 

## Δείτε επίσης

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Κλάση [ResultValueTask](../)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)