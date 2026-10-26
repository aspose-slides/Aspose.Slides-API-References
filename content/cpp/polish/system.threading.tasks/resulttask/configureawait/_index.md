---
title: ConfigureAwait()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Konfiguruje sposób, w jaki oczekiwania na tym zadaniu wynikowym zachowują się względem przechwycenia kontekstu.
type: docs
weight: 27
url: /pl/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const metoda


Konfiguruje sposób, w jaki oczekiwania na tym zadaniu wynikowym zachowują się względem przechwycenia kontekstu.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Czy kontynuować w przechwyconym kontekście |

### Wartość zwracana

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Skonfigurowany awaitable dla wyniku
## Uwagi



Umożliwia to precyzyjną kontrolę przepływu kontekstu w wzorcach async/await.

## Zobacz także

* Klasa [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Klasa [ResultTask](../)
* Przestrzeń nazw [System::Threading::Tasks](../../)
* Biblioteka [Aspose.Slides](../../../)