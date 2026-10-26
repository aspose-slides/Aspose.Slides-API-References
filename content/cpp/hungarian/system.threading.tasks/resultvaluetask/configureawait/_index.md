---
title: ConfigureAwait()
second_title: Aspose.Slides C++ API referencia
description: Beállít egy várakozót ehhez a feladathoz.
type: docs
weight: 92
url: /hu/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const metódus

Beállít egy várakozót ehhez a feladathoz.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true, ha megpróbálja a folytatást visszairányítani a rögzített eredeti kontextusba; egyébként false. |

### Visszatérési érték

ConfiguredResultValueTaskAwaitable<T> Egy objektum, amely beállítja, hogyan viselkednek a várakozók ehhez a feladathoz.

## Lásd még

* Osztály [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Osztály [ResultValueTask](../)
* Névtér [System::Threading::Tasks](../../)
* Könyvtár [Aspose.Slides](../../../)