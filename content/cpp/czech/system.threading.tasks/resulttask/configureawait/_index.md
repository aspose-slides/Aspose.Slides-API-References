---
title: ConfigureAwait()
second_title: Aspose.Slides pro C++ API Reference
description: Nastavuje, jak mají awaity na tomto result tasku fungovat v souvislosti se zachycením kontextu.
type: docs
weight: 27
url: /cs/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const metoda

Nastavuje, jak mají awaity na tomto result tasku fungovat v souvislosti se zachycením kontextu.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Zda pokračovat v zachyceném kontextu |

### Návratová hodnota

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Konfigurovaný awaitable pro výsledek

## Poznámky

Toto umožňuje jemnou kontrolu toku kontextu pro vzory async/await.

## Viz také

* Třída [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Třída [ResultTask](../)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)