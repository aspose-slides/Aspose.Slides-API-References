---
title: WaitAll()
second_title: Aspose.Slides C++ API Referencia
description: Megvárja az összes megadott Task objektum végrehajtásának befejezését.
type: docs
weight: 170
url: /hu/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) függvény

Várja meg az összes megadott [Task](../task/) objektum végrehajtásának befejezését.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Egy tömb a [Task](../task/) példányokból, amelyeken várni kell. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Egy [CancellationToken](../../system.threading/cancellationtoken/) amelyre figyelni kell, miközben a feladatok befejezésére várunk. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) függvény

Várja meg az összes megadott [Task](../task/) objektum végrehajtásának befejezését.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Egy tömb a [Task](../task/) példányokból, amelyeken várni kell. |

## Lásd még

* Típusdefiníció [ArrayPtr](../../system/arrayptr/)
* Típusdefiníció [TaskPtr](../../system/taskptr/)
* Osztály [CancellationToken](../../system.threading/cancellationtoken/)
* Névtér [System::Threading::Tasks](../)
* Könyvtár [Aspose.Slides](../../)