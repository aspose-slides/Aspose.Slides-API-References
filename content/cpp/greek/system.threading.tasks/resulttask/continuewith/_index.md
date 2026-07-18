---
title: ContinueWith()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί μια συνέχεια που εκτελείται όταν ολοκληρωθεί η εργασία αποτελέσματος.
type: docs
weight: 40
url: /el/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) method

Δημιουργεί μια συνέχεια που εκτελείται όταν ολοκληρωθεί η εργασία αποτελέσματος.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Δράση που εκτελείται όταν ολοκληρωθεί αυτή η εργασία, λαμβάνοντας αυτήν την εργασία αποτελέσματος |

### Τιμή Επιστροφής

TaskPtr Μία νέα εργασία που αντιπροσωπεύει τη συνέχεια

## Σχόλια

Η δράση συνέχειας λαμβάνει αυτό το [ResultTask](../) για να έχει πρόσβαση στην τιμή του αποτελέσματος 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) method

Δημιουργεί μια συνέχεια που εκτελείται όταν ολοκληρωθεί η εργασία αποτελέσματος.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TNewResult | Τύπος αποτελέσματος της συνέχειας εργασίας |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Συνάρτηση για λήψη του αποτελέσματος συνέχειας όταν ολοκληρωθεί αυτή η εργασία, λαμβάνοντας αυτήν την εργασία αποτελέσματος |

### Τιμή Επιστροφής

RTaskPtr Μία νέα εργασία που αντιπροσωπεύει τη συνέχεια

## Σχόλια

Η συνάρτηση συνέχειας λαμβάνει αυτό το [ResultTask](../) για να έχει πρόσβαση στην τιμή του αποτελέσματος 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) method

Δημιουργεί μια συνέχεια που εκτελείται όταν ολοκληρωθεί η εργασία.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Δράση που εκτελείται όταν ολοκληρωθεί αυτή η εργασία |

### Τιμή Επιστροφής

TaskPtr Μία νέα εργασία που αντιπροσωπεύει τη συνέχεια

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) method

Δημιουργεί μια συνέχεια που εκτελείται όταν ολοκληρωθεί η εργασία.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TResult | Ένας τύπος αποτελέσματος εργασίας |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Συνάρτηση για λήψη του αποτελέσματος όταν ολοκληρωθεί αυτή η εργασία |

### Τιμή Επιστροφής

RTaskPtr Μία νέα εργασία που αντιπροσωπεύει τη συνέχεια

## Δείτε επίσης

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Κλάση [ResultTask](../)
* Κλάση [Func](../../../system/func/)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)