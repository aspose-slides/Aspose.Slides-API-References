---
title: ConfigureAwait()
second_title: Aspose.Slides für C++ API-Referenz
description: Konfiguriert einen Awaiter für diese Aufgabe.
type: docs
weight: 92
url: /de/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const Methode

Konfiguriert einen Awaiter für diese Aufgabe.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true, um zu versuchen, die Fortsetzung zurück in den ursprünglich erfassten Kontext zu marshallen; andernfalls false. |

### Rückgabewert

ConfiguredResultValueTaskAwaitable<T> Ein Objekt, das konfiguriert, wie Awaiter für diese Aufgabe sich verhalten.

## Siehe auch

* Klasse [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Klasse [ResultValueTask](../)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)