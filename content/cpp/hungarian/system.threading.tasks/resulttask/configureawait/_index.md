---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API-referencia
description: Beállítja, hogyan kell viselkednie az ebben a result task-ben lévő await-eknek a kontextus rögzítése tekintetében.
type: docs
weight: 27
url: /hu/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const metódus

Beállítja, hogyan kell viselkedniük az ebben a result task-ben lévő await-eknek a kontextus rögzítése tekintetében.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Megadja, hogy folytatódjon-e a rögzített kontextuson |

### Visszatérési érték

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Egy a result számára konfigurált awaitable

## Megjegyzés

Ez lehetővé teszi a finomhangolt vezérlést a kontextusáramlás felett az async/await minták esetén

## Lásd még

* Osztály [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Osztály [ResultTask](../)
* Névtere [System::Threading::Tasks](../../)
* Könyvtár [Aspose.Slides](../../../)