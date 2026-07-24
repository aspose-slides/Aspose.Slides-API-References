---
title: WhenAny()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen Task, der beendet wird, wenn einer der bereitgestellten Tasks abgeschlossen ist.
type: docs
weight: 209
url: /de/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) Funktion

Erstellt ein Task, das abgeschlossen wird, wenn eine der bereitgestellten tasks abgeschlossen ist.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Die tasks, auf die gewartet wird, bis sie abgeschlossen sind. |

### Rückgabewert

Ein Task, der den Abschluss einer der bereitgestellten tasks darstellt.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) Funktion

Erstellt ein Task, das abgeschlossen wird, wenn eine der bereitgestellten tasks abgeschlossen ist.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Die tasks, auf die gewartet wird, bis sie abgeschlossen sind. |

### Rückgabewert

Ein Task, der den Abschluss einer der bereitgestellten tasks darstellt.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) Funktion

Erstellt ein Task, das abgeschlossen wird, wenn eine der bereitgestellten tasks abgeschlossen ist.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TResult | Der Typ des Ergebnisses des abgeschlossenen Task. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Die tasks, auf die gewartet wird, bis sie abgeschlossen sind. |

### Rückgabewert

Ein Task, das das zuerst abgeschlossene Task zurückgibt, wenn irgendein Task abgeschlossen ist.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) Funktion

Erstellt ein Task, das abgeschlossen wird, wenn eine der bereitgestellten tasks abgeschlossen ist.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TResult | Der Typ des Ergebnisses des abgeschlossenen Task. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Die tasks, auf die gewartet wird, bis sie abgeschlossen sind. |

### Rückgabewert

Ein Task, das das zuerst abgeschlossene Task zurückgibt, wenn irgendein Task abgeschlossen ist.

## Siehe auch

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Klasse [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)