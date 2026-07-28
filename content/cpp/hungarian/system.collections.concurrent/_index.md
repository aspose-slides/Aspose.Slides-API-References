---
title: "System::Collections::Concurrent"
second_title: Aspose.Slides C++ API Referencia
description: 
type: docs
weight: 313
url: /hu/system.collections.concurrent/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [ConcurrentDictionary](./concurrentdictionary/) | Szálbiztos szótár implementáció. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy assertion hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az osztályt függvények argumentumaként átadni. |