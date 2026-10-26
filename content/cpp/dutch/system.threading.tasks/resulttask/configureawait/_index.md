---
title: ConfigureAwait()
second_title: Aspose.Slides voor C++ API-referentie
description: Configureert hoe awaits op deze resulttaak zich moeten gedragen met betrekking tot het vastleggen van de context.
type: docs
weight: 27
url: /nl/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const methode

Configureert hoe `await`s op deze resulttaak zich moeten gedragen met betrekking tot het vastleggen van de context.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Of er voortgegaan moet worden op de vastgelegde context |

### Retourwaarde

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Een geconfigureerde awaitable voor het resultaat

## Opmerkingen

Dit maakt fijnmazige controle over de contextstroom mogelijk voor async/await-patronen 

## Zie ook

* Klasse [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Klasse [ResultTask](../)
* Naamruimte [System::Threading::Tasks](../../)
* Bibliotheek [Aspose.Slides](../../../)