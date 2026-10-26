---
title: QueueUserWorkItem()
second_title: Aspose.Slides C++ API referencia
description: A munkadarabot sorba helyezi, amely callback-et tartalmaz paraméter nélkül.
type: docs
weight: 14
url: /hu/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) metódus


A munkadarabot sorba helyezi, amely callback-et tartalmaz paraméter nélkül.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback függvény, amely feladatként használható. |

### Visszatérési érték

Mindig true értéket ad vissza.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metódus


A munkadarabot sorba helyezi, amely callback-et tartalmaz paraméter nélkül.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback függvény, amely feladatként használható. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Feladatfüggvény paramétere. |

### Visszatérési érték

Mindig true értéket ad vissza.

## Lásd még

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ThreadPool](../)
* Osztály [Object](../../../system/object/)
* Névtér [System::Threading](../../)
* Library [Aspose.Slides](../../../)