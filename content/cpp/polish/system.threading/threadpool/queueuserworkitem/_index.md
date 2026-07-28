---
title: QueueUserWorkItem()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Umieszcza element pracy w kolejce, który jest dostępny z wywołaniem zwrotnym bez parametru.
type: docs
weight: 14
url: /pl/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) metoda

Umieszcza element pracy w kolejce, który jest dostępny z wywołaniem zwrotnym bez parametru.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Funkcja wywołania zwrotnego używana jako zadanie. |

### Wartość zwracana

Zawsze zwraca true.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metoda

Umieszcza element pracy w kolejce, który jest dostępny z wywołaniem zwrotnym bez parametru.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Funkcja wywołania zwrotnego używana jako zadanie. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Parametr funkcji zadania. |

### Wartość zwracana

Zawsze zwraca true.

## Zobacz także

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ThreadPool](../)
* Klasa [Object](../../../system/object/)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)