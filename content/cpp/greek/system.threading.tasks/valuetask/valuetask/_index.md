---
title: ValueTask()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα κενό, μη αρχικοποιημένο ValueTask.
type: docs
weight: 1
url: /el/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() κατασκευαστής

Δημιουργεί ένα κενό, μη αρχικοποιημένο [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Παρατηρήσεις

Η εργασία δεν έχει ολοκληρωθεί και δεν περιέχει αποτέλεσμα. Η προσπάθεια λήψης του αποτελέσματος θα προκαλέσει εξαίρεση.

## ValueTask::ValueTask(const TaskPtr\&) κατασκευαστής

Δημιουργεί ένα [ValueTask](../) από έναν κοινό δείκτη προς ένα [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | Το task για περιτύλιξη. Μπορεί να είναι null για ένα κενό task. |

## Παρατηρήσεις

Το [ValueTask](../) θα αντιπροσωπεύει την κατάσταση του δοθέντος task.

## Δείτε επίσης

* Τύπο [TaskPtr](../../../system/taskptr/)
* Κλάση [ValueTask](../)
* Χώρος ονομάτων [System::Threading::Tasks](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)