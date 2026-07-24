---
title: ConfigureAwait()
second_title: Aspose.Slides für C++ API-Referenz
description: Konfiguriert, wie Await-Operationen auf diesem ResultTask sich in Bezug auf die Kontextaufnahme verhalten sollen.
type: docs
weight: 27
url: /de/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const Methode

Konfiguriert, wie Await-Operationen auf diesem ResultTask sich in Bezug auf die Kontextaufnahme verhalten sollen.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Ob im erfassten Kontext fortgesetzt werden soll |

### Rückgabewert

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Ein konfigurierbarer Awaitable für das Ergebnis

## Bemerkungen

Dies ermöglicht eine feinkörnige Steuerung des Kontextflusses für async/await-Muster

## Siehe auch

* Klasse [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Klasse [ResultTask](../)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)