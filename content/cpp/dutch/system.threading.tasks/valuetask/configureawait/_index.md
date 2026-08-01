---
title: ConfigureAwait()
second_title: Aspose.Slides voor C++ API-referentie
description: Configureert een awaiter voor deze taak.
type: docs
weight: 79
url: /nl/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const methode

Configureert een awaiter voor deze taak.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true om te proberen de voortzetting terug te sturen naar de oorspronkelijke context die is vastgelegd; anders false. |

### Retourwaarde

ConfiguredValueTaskAwaitable Een object dat configureert hoe wachters zich gedragen voor deze taak.

## Zie ook

* Klasse [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Klasse [ValueTask](../)
* Naamruimte [System::Threading::Tasks](../../)
* Bibliotheek [Aspose.Slides](../../../)