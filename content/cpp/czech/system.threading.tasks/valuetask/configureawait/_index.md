---
title: ConfigureAwait()
second_title: Aspose.Slides pro C++ API Reference
description: Konfiguruje awaiter pro tento úkol.
type: docs
weight: 79
url: /cs/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const metoda


Konfiguruje awaiter pro tento úkol.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true pro pokus o přenos pokračování zpět do původního zachyceného kontextu; jinak false. |

### Návratová hodnota

ConfiguredValueTaskAwaitable Objekt, který konfiguruje, jak se awaitery chovají pro tento úkol.

## Viz také

* Třída [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Třída [ValueTask](../)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)