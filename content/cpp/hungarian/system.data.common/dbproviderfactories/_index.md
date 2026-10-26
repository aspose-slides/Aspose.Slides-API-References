---
title: DbProviderFactories
second_title: Aspose.Slides C++ API-referencia
description: "API az adatbázis-szolgáltató gyárak lekéréséhez. Az osztály objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az osztály függvényeknek argumentumként történő átadásához."
type: docs
weight: 53
url: /hu/system.data.common/dbproviderfactories/
---
## DbProviderFactories osztály


API a DB provider factory-k lekéréséhez. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az osztály függvényeknek argumentumként történő átadásához.

```cpp
class DbProviderFactories
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | Név alapján lekéri a DB provider factory-t. |
## Lásd még

* Névtér [System::Data::Common](../)
* Könyvtár [Aspose.Slides](../../)