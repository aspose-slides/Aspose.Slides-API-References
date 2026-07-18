---
title: WaitAll()
second_title: Aspose.Slides για C++ Αναφορά API
description: Περιμένει μέχρι όλα τα παρεχόμενα αντικείμενα Task να ολοκληρώσουν την εκτέλεση.
type: docs
weight: 170
url: /el/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) function

Περιμένει μέχρι όλα τα παρεχόμενα [Task](../task/) αντικείμενα να ολοκληρώσουν την εκτέλεση.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Ένας πίνακας από στιγμιότυπα [Task](../task/) στα οποία θα περιμένει. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Ένα [CancellationToken](../../system.threading/cancellationtoken/) που παρακολουθείται ενώ περιμένει να ολοκληρωθούν οι εργασίες. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) function

Περιμένει μέχρι όλα τα παρεχόμενα [Task](../task/) αντικείμενα να ολοκληρώσουν την εκτέλεση.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Ένας πίνακας από στιγμιότυπα [Task](../task/) στα οποία θα περιμένει. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Κλάση [CancellationToken](../../system.threading/cancellationtoken/)
* Χώρος ονομάτων [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)