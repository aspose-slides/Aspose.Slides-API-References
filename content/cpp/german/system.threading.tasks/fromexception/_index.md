---
title: FromException()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine Aufgabe, die mit einer angegebenen Ausnahme abgeschlossen wurde.
type: docs
weight: 131
url: /de/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) Funktion

Erstellt eine Aufgabe, die mit einer angegebenen Ausnahme abgeschlossen wurde.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Die Ausnahme, mit der die Aufgabe abgeschlossen wird. |

### Rückgabewert

Eine fehlerhafte Aufgabe.

## System::Threading::Tasks::FromException(const Exception\&) Funktion

Erstellt eine Aufgabe, die mit einer angegebenen Ausnahme und einem Ergebnistyp abgeschlossen wurde.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TResult | Der Typ des Aufgabenergebnisses. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Die Ausnahme, mit der die Aufgabe abgeschlossen wird. |

### Rückgabewert

Eine fehlerhafte Aufgabe mit dem angegebenen Ergebnistyp.

## Siehe auch

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)