---
title: ConfigureAwait()
second_title: Aspose.Slides C++ API Referencia
description: Beállít egy várakozót ehhez a feladathoz.
type: docs
weight: 79
url: /hu/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const metódus

Beállít egy várakozót ehhez a feladathoz.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true, ha megpróbálja a folytatást visszakerülni a rögzített eredeti környezetbe; egyébként false. |

### Visszatérési érték

ConfiguredValueTaskAwaitable Egy objektum, amely beállítja, hogyan viselkednek a várakozók ebben a feladatban.

## Lásd még

* Osztály [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Osztály [ValueTask](../)
* Névtér [System::Threading::Tasks](../../)
* Könyvtár [Aspose.Slides](../../../)