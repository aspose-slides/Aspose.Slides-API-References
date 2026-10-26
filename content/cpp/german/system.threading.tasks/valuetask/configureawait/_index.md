---
title: ConfigureAwait()
second_title: Aspose.Slides für C++ API-Referenz
description: Konfiguriert einen Awaiter für diese Aufgabe.
type: docs
weight: 79
url: /de/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const Methode


Konfiguriert einen Awaiter für diese Aufgabe.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true, um zu versuchen, die Fortsetzung zurück in den ursprünglich erfassten Kontext zu überführen; andernfalls false. |

### Rückgabewert

ConfiguredValueTaskAwaitable Ein Objekt, das konfiguriert, wie Awaiter für diese Aufgabe funktionieren.

## Siehe auch

* Klasse [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Klasse [ValueTask](../)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)