---
title: QueueUserWorkItem()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Dodaje element pracy do kolejki.
type: docs
weight: 1
url: /pl/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metoda

Dodaje element pracy do kolejki.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Funkcja zwrotna do wykonania. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument funkcji zwrotnej. |

### Zwracana wartość

Zawsze zwraca true.

## Zobacz także

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ThreadPoolImpl](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)