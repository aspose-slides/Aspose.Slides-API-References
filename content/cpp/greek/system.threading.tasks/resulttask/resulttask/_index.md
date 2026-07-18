---
title: ResultTask()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα ResultTask με μια συνάρτηση που επιστρέφει μια τιμή.
type: docs
weight: 1
url: /el/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) κατασκευαστής


Δημιουργεί ένα [ResultTask](../) με μια συνάρτηση που επιστρέφει μια τιμή.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | Η συνάρτηση που θα εκτελεστεί ασύγχρονα και επιστρέφει ένα αποτέλεσμα |

## ResultTask::ResultTask() κατασκευαστής


Εσωτερική υλοποίηση. Δεν επιτρέπεται για κώδικα χρήστη.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Παρατηρήσεις


Εσωτερικός κατασκευαστής για τη δημιουργία ακαθόριστων εργασιών αποτελέσματος 
## ResultTask::ResultTask(const T\&) κατασκευαστής


Εσωτερικός κατασκευαστής για τη δημιουργία εργασιών αποτελέσματος με συγκεκριμένο αποτέλεσμα.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Δείτε επίσης

* Κλάση [Func](../../../system/func/)
* Κλάση [ResultTask](../)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)