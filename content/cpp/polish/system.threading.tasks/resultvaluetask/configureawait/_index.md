---
title: ConfigureAwait()
second_title: Referencja API Aspose.Slides dla C++
description: Konfiguruje oczekującego dla tego zadania.
type: docs
weight: 92
url: /pl/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const metoda

Konfiguruje oczekującego dla tego zadania.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true, aby spróbować przekazać kontynuację z powrotem do pierwotnego przechwyconego kontekstu; w przeciwnym razie false. |

### Wartość zwracana

ConfiguredResultValueTaskAwaitable<T> Obiekt, który konfiguruje jak oczekujący zachowują się dla tego zadania.

## Zobacz także

* Klasa [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Klasa [ResultValueTask](../)
* Przestrzeń nazw [System::Threading::Tasks](../../)
* Biblioteka [Aspose.Slides](../../../)