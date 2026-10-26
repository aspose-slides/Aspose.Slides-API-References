---
title: QueueUserWorkItem()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein Arbeitselement in die Warteschlange ein, das mit einem Callback ohne Parameter vorhanden ist.
type: docs
weight: 14
url: /de/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) Methode

Fügt ein Arbeitselement in die Warteschlange ein, das mit einem Callback ohne Parameter vorhanden ist.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback-Funktion, die als Aufgabe verwendet wird. |

### Rückgabewert

Gibt immer true zurück.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) Methode

Fügt ein Arbeitselement in die Warteschlange ein, das mit einem Callback ohne Parameter vorhanden ist.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback-Funktion, die als Aufgabe verwendet wird. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Parameter der Jobfunktion. |

### Rückgabewert

Gibt immer true zurück.

## Siehe auch

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ThreadPool](../)
* Klasse [Object](../../../system/object/)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)