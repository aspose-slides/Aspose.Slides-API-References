---
title: QueueUserWorkItem()
second_title: Aspose.Slides voor C++ API-referentie
description: Plaatst een werkitem in de wachtrij dat wordt geleverd met een callback zonder parameter.
type: docs
weight: 14
url: /nl/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) methode


Plaatst een werkitem in de wachtrij dat wordt geleverd met een callback zonder parameter.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback-functie die als taak wordt gebruikt. |

### Retourwaarde

Geeft altijd true terug.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) methode


Plaatst een werkitem in de wachtrij dat wordt geleverd met een callback zonder parameter.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback-functie die als taak wordt gebruikt. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Parameter voor de taakfunctie. |

### Retourwaarde

Geeft altijd true terug.

## Zie ook

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ThreadPool](../)
* Klasse [Object](../../../system/object/)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)