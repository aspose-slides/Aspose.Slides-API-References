---
title: GetAwaiter()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει έναν awaiter για αυτήν την εργασία αποτελέσματος για χρήση με Await.
type: docs
weight: 53
url: /el/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const μέθοδος

Λαμβάνει έναν awaiter για αυτήν την εργασία αποτελέσματος για χρήση με Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```

### Τιμή Επιστροφής

Runtime::CompilerServices::ResultTaskAwaiter<T> Μία παρουσία awaiter που επιστρέφει το αποτέλεσμα

## Παρατηρήσεις

Όταν γίνεται await, η coroutine θα συνεχίσει με τη διαθέσιμη τιμή του αποτελέσματος

## Δείτε επίσης

* Κλάση [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Κλάση [ResultTask](../)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)