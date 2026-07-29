---
title: QueueUserWorkItem()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till arbetsobjekt i kön som är närvarande med återanrop utan parameter.
type: docs
weight: 14
url: /sv/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) metod


Lägger till arbetsobjekt i kön som är närvarande med återanrop utan parameter.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback-funktion som ska användas som ett jobb. |

### Returvärde

Returnerar alltid true.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metod


Lägger till arbetsobjekt i kön som är närvarande med återanrop utan parameter.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback-funktion som ska användas som ett jobb. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Parameter för jobbfunktion. |

### Returvärde

Returnerar alltid true.

## Se även

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ThreadPool](../)
* Klass [Object](../../../system/object/)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)