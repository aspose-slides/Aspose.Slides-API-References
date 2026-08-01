---
title: ConfigureAwait()
second_title: Aspose.Slides voor C++ API-referentie
description: Configureert een awaiter voor deze taak.
type: docs
weight: 92
url: /nl/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const methode

Configureert een awaiter voor deze taak.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true om te proberen de voortzetting terug te marshallen naar de oorspronkelijke vastgelegde context; anders false. |

### Retourwaarde

ConfiguredResultValueTaskAwaitable<T> Een object dat configureert hoe awaiters zich gedragen voor deze taak.

## Zie ook

* Klasse [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Klasse [ResultValueTask](../)
* Naamruimte [System::Threading::Tasks](../../)
* Bibliotheek [Aspose.Slides](../../../)