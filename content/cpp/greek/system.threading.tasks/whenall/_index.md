---
title: WhenAll()
second_title: Aspose.Slides για το C++ API
description: Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθούν όλες οι παρεχόμενες εργασίες.
type: docs
weight: 196
url: /el/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) συνάρτηση


Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθούν όλες οι παρεχόμενες εργασίες.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Οι εργασίες για τις οποίες θα περιμένει η ολοκλήρωση. |

### Τιμή Επιστροφής

Μια εργασία που αντιπροσωπεύει την ολοκλήρωση όλων των παρεχόμενων εργασιών.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) συνάρτηση


Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθούν όλες οι παρεχόμενες εργασίες.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Οι εργασίες για τις οποίες θα περιμένει η ολοκλήρωση. |

### Τιμή Επιστροφής

Μια εργασία που αντιπροσωπεύει την ολοκλήρωση όλων των παρεχόμενων εργασιών.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) συνάρτηση


Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθούν όλες οι παρεχόμενες εργασίες.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TResult | Ο τύπος των αποτελεσμάτων των ολοκληρωμένων εργασιών. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Οι εργασίες για τις οποίες θα περιμένει η ολοκλήρωση. |

### Τιμή Επιστροφής

Μια εργασία που επιστρέφει έναν πίνακα με όλα τα αποτελέσματα όταν ολοκληρωθούν όλες οι εργασίες.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) συνάρτηση


Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθούν όλες οι παρεχόμενες εργασίες.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TResult | Ο τύπος των αποτελεσμάτων των ολοκληρωμένων εργασιών. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Οι εργασίες για τις οποίες θα περιμένει η ολοκλήρωση. |

### Τιμή Επιστροφής

Μια εργασία που επιστρέφει έναν πίνακα με όλα τα αποτελέσματα όταν ολοκληρωθούν όλες οι εργασίες.

## Δείτε επίσης

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Κλάση [IEnumerable](../../system.collections.generic/ienumerable/)
* Χώρος ονομάτων [System::Threading::Tasks](../)
* Βιβλιοθήκη [Aspose.Slides](../../)