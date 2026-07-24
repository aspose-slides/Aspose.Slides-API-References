---
title: Yield()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine await-fähige Aufgabe, die bei await asynchron zum aktuellen Kontext zurückkehrt.
type: docs
weight: 222
url: /de/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() Funktion


Erstellt eine await-fähige Aufgabe, die bei await asynchron zum aktuellen Kontext zurückkehrt.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### Rückgabewert

Ein YieldAwaitable, das await-bar ist, um die Kontrolle zurückzugeben.
## Bemerkungen



Diese Methode ist nützlich, um eine asynchrone Methode dazu zu zwingen, die Kontrolle zu übergeben, sodass andere ausstehende Arbeiten verarbeitet werden können, bevor fortgefahren wird. 
## Siehe auch

* Klasse [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Namensraum [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)