---
title: QueueUserWorkItem()
second_title: Aspose.Slides pro C++ API Reference
description: Umístí úkol do fronty s callbackem bez parametru.
type: docs
weight: 14
url: /cs/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) metoda

Umístí úkol do fronty s callbackem bez parametru.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Funkce callback, která se použije jako úloha. |

### Návratová hodnota

Vždy vrací true.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metoda

Umístí úkol do fronty s callbackem bez parametru.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Funkce callback, která se použije jako úloha. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Parametr funkce úlohy. |

### Návratová hodnota

Vždy vrací true.

## Viz také

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ThreadPool](../)
* Class [Object](../../../system/object/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)