---
title: WaitAny()
second_title: Αναφορά API Aspose.Slides για C++
description: Περιμένει για οποιοδήποτε από τα παρεχόμενα αντικείμενα Task να ολοκληρώσει την εκτέλεση.
type: docs
weight: 183
url: /el/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) συνάρτηση


Περιμένει για οποιοδήποτε από τα παρεχόμενα [Task](../task/) αντικείμενα να ολοκληρώσει την εκτέλεση.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Ένας πίνακας από αντικείμενα [Task](../task/) στους οποίους θα περιμένει. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Ένα [CancellationToken](../../system.threading/cancellationtoken/) προς παρακολούθηση ενώ περιμένει την ολοκλήρωση των tasks. |

### Τιμή Επιστροφής

Ο δείκτης της ολοκληρωμένης εργασίας στον πίνακα tasks.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) συνάρτηση


Περιμένει για οποιοδήποτε από τα παρεχόμενα [Task](../task/) αντικείμενα να ολοκληρώσει την εκτέλεση.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Ένας πίνακας από αντικείμενα [Task](../task/) στους οποίους θα περιμένει. |

### Τιμή Επιστροφής

Ο δείκτης της ολοκληρωμένης εργασίας στον πίνακα tasks.

## Δείτε επίσης

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)