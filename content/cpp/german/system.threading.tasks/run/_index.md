---
title: Run()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die angegebene Arbeit in die Thread-Pool-Warteschlange und gibt ein Task-Handle für diese Arbeit zurück.
type: docs
weight: 157
url: /de/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) Funktion


Stellt die angegebene Arbeit in die Thread-Pool-Warteschlange und gibt ein [Task](../task/)-Handle für diese Arbeit zurück.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Die Arbeit, die asynchron ausgeführt werden soll. |

### Rückgabewert

Ein [Task](../task/), der die in die Thread-Pool-Warteschlange eingestellte Arbeit repräsentiert.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) Funktion


Stellt die angegebene Arbeit in die Thread-Pool-Warteschlange und gibt ein [Task](../task/)-Handle für diese Arbeit zurück.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Die Arbeit, die asynchron ausgeführt werden soll. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Ein Abbruch-Token, das verwendet werden kann, um die Arbeit abzubrechen, wenn sie noch nicht gestartet wurde. |

### Rückgabewert

Ein [Task](../task/), der die in die Thread-Pool-Warteschlange eingestellte Arbeit repräsentiert.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) Funktion


Stellt die angegebene Arbeit in die Thread-Pool-Warteschlange und gibt einen Proxy für das von der Funktion zurückgegebene [Task](../task/) zurück.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Die Arbeit, die asynchron ausgeführt wird und ein [Task](../task/) zurückgibt. |

### Rückgabewert

Ein [Task](../task/), der einen Proxy für das von der Funktion zurückgegebene [Task](../task/) darstellt.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) Funktion


Stellt die angegebene Arbeit in die Thread-Pool-Warteschlange und gibt ein Task<TResult>-Handle für diese Arbeit zurück.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TResult | Der Typ des von der Aufgabe zurückgegebenen Ergebnisses. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Die Arbeit, die asynchron ausgeführt wird. |

### Rückgabewert

Ein Task<TResult>, der die in die Thread-Pool-Warteschlange eingestellte Arbeit repräsentiert.

## Siehe auch

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Klasse [CancellationToken](../../system.threading/cancellationtoken/)
* Klasse [Func](../../system/func/)
* Namensraum [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)