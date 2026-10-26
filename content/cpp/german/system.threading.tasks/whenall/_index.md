---
title: WhenAll()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Aufgabe, die abgeschlossen wird, sobald alle übergebenen Aufgaben beendet sind.
type: docs
weight: 196
url: /de/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) Funktion

Erstellt eine Aufgabe, die abgeschlossen wird, sobald alle übergebenen Aufgaben beendet sind.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Die Aufgaben, auf die gewartet wird, bis sie abgeschlossen sind. |

### Rückgabewert

Eine Aufgabe, die den Abschluss aller übergebenen Aufgaben darstellt.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) Funktion

Erstellt eine Aufgabe, die abgeschlossen wird, sobald alle übergebenen Aufgaben beendet sind.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Die Aufgaben, auf die gewartet wird, bis sie abgeschlossen sind. |

### Rückgabewert

Eine Aufgabe, die den Abschluss aller übergebenen Aufgaben darstellt.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) Funktion

Erstellt eine Aufgabe, die abgeschlossen wird, sobald alle übergebenen Aufgaben beendet sind.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TResult | Der Typ der Ergebnisse der abgeschlossenen Aufgaben. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Die Aufgaben, auf die gewartet wird, bis sie abgeschlossen sind. |

### Rückgabewert

Eine Aufgabe, die ein Array aller Ergebnisse zurückgibt, wenn alle Aufgaben abgeschlossen sind.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) Funktion

Erstellt eine Aufgabe, die abgeschlossen wird, sobald alle übergebenen Aufgaben beendet sind.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TResult | Der Typ der Ergebnisse der abgeschlossenen Aufgaben. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Die Aufgaben, auf die gewartet wird, bis sie abgeschlossen sind. |

### Rückgabewert

Eine Aufgabe, die ein Array aller Ergebnisse zurückgibt, wenn alle Aufgaben abgeschlossen sind.

## Siehe auch

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Klasse [IEnumerable](../../system.collections.generic/ienumerable/)
* Namensraum [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)