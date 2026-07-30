---
title: ConfigureAwait()
second_title: Aspose.Slides pro C++ API Reference
description: Konfiguruje awaiter pro tento úkol.
type: docs
weight: 92
url: /cs/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const metoda

Konfiguruje awaiter pro tento úkol.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true pro pokus o přenesení pokračování zpět do původního zachyceného kontextu; jinak false. |

### Návratová hodnota

ConfiguredResultValueTaskAwaitable<T> Objekt, který konfiguruje chování awaiterů pro tento úkol.

## Viz také

* Třída [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Třída [ResultValueTask](../)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)