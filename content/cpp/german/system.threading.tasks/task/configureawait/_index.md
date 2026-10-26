---
title: ConfigureAwait()
second_title: Aspose.Slides für C++ API-Referenz
description: Konfiguriert, wie Await-Aufrufe für diese Aufgabe im Hinblick auf die Kontextaufnahme verhalten sollen.
type: docs
weight: 144
url: /de/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const Methode

Konfiguriert, wie Await-Aufrufe für diese Aufgabe im Hinblick auf die Kontextaufnahme verhalten sollen.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Gibt an, ob im erfassten Kontext fortgesetzt werden soll |

### Rückgabewert

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) Ein konfigurierter Awaitable

## Siehe auch

* Klasse [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* Klasse [Task](../)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)