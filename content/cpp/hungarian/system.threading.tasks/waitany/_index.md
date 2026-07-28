---
title: WaitAny()
second_title: Aspose.Slides C++ API referencia
description: Várja, hogy a megadott Task objektumok közül bármelyik befejezze a végrehajtást.
type: docs
weight: 183
url: /hu/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) függvény

Várja, hogy a megadott [Task](../task/) objektumok közül bármelyik befejezze a végrehajtást.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Egy [Task](../task/) példányokból álló tömb, amelyen várni kell. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | [CancellationToken](../../system.threading/cancellationtoken/) a feladatok befejeződéséig tartó várakozás során megfigyelendő. |

### Visszatérési érték

A befejezett feladat indexe a feladatok tömbjében.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) függvény

Várja, hogy a megadott [Task](../task/) objektumok közül bármelyik befejezze a végrehajtást.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Egy [Task](../task/) példányokból álló tömb, amelyen várni kell. |

### Visszatérési érték

A befejezett feladat indexe a feladatok tömbjében.

## Kapcsolódóak

* Típusdefiníció [ArrayPtr](../../system/arrayptr/)
* Típusdefiníció [TaskPtr](../../system/taskptr/)
* Osztály [CancellationToken](../../system.threading/cancellationtoken/)
* Névtér [System::Threading::Tasks](../)
* Könyvtár [Aspose.Slides](../../)