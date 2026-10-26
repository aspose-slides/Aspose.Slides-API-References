---
title: ContinueWith()
second_title: Aspose.Slides για C++ API Reference
description: Δημιουργεί μια συνέχεια που εκτελείται όταν ολοκληρωθεί η εργασία.
type: docs
weight: 118
url: /el/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) μέθοδος

Δημιουργεί μια συνέχεια που εκτελείται όταν ολοκληρωθεί η εργασία.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action to execute when this task completes |

### Τιμή Επιστροφής

TaskPtr Μια νέα εργασία που αντιπροσωπεύει τη συνέχεια

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) μέθοδος

Δημιουργεί μια συνέχεια που εκτελείται όταν ολοκληρωθεί η εργασία.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TResult | A type of task result |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Function to get result when this task completes |

### Τιμή Επιστροφής

RTaskPtr Μια νέα εργασία που αντιπροσωπεύει τη συνέχεια

## Δείτε επίσης

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Κλάση [Task](../)
* Κλάση [Func](../../../system/func/)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)