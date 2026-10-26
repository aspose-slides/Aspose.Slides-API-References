---
title: WhenAny()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθεί οποιαδήποτε από τις παρεχόμενες εργασίες.
type: docs
weight: 209
url: /el/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) συνάρτηση

Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθεί οποιαδήποτε από τις παρεχόμενες εργασίες.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Οι εργασίες προς αναμονή για ολοκλήρωση. |

### Τιμή Επιστροφής

Μία εργασία που αντιπροσωπεύει την ολοκλήρωση μιας από τις παρεχόμενες εργασίες.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) συνάρτηση

Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθεί οποιαδήποτε από τις παρεχόμενες εργασίες.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Οι εργασίες προς αναμονή για ολοκλήρωση. |

### Τιμή Επιστροφής

Μία εργασία που αντιπροσωπεύει την ολοκλήρωση μιας από τις παρεχόμενες εργασίες.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) συνάρτηση

Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθεί οποιαδήποτε από τις παρεχόμενες εργασίες.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TResult | Ο τύπος του αποτελέσματος της ολοκληρωμένης εργασίας. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Οι εργασίες προς αναμονή για ολοκλήρωση. |

### Τιμή Επιστροφής

Μία εργασία που επιστρέφει την πρώτη ολοκληρωμένη εργασία όταν ολοκληρωθεί οποιαδήποτε εργασία.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) συνάρτηση

Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθεί οποιαδήποτε από τις παρεχόμενες εργασίες.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TResult | Ο τύπος του αποτελέσματος της ολοκληρωμένης εργασίας. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Οι εργασίες προς αναμονή για ολοκλήρωση. |

### Τιμή Επιστροφής

Μία εργασία που επιστρέφει την πρώτη ολοκληρωμένη εργασία όταν ολοκληρωθεί οποιαδήποτε εργασία.

## Δείτε επίσης

* Ορισμός τύπου [RTaskPtr](../../system/rtaskptr/)
* Ορισμός τύπου [TaskPtr](../../system/taskptr/)
* Ορισμός τύπου [SharedPtr](../../system/sharedptr/)
* Ορισμός τύπου [ArrayPtr](../../system/arrayptr/)
* Κλάση [IEnumerable](../../system.collections.generic/ienumerable/)
* Χώρος ονομάτων [System::Threading::Tasks](../)
* Βιβλιοθήκη [Aspose.Slides](../../)