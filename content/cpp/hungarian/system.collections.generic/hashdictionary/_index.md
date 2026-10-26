---
title: HashDictionary
second_title: Aspose.Slides C++ API Referencia
description: "Egy helykitöltő a HashDictionary osztályhoz (jelenleg nincs megvalósítva). Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat okoz. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 209
url: /hu/system.collections.generic/hashdictionary/
---
## HashDictionary osztály

A [HashDictionary](./) osztályhoz tartozó helykitöltő (jelenleg nincs megvalósítva). Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az osztály függvényeknek argumentumként való átadásához.

```cpp
template<typename T,typename T2>class HashDictionary
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| T2 [operator[]](./operator[]/)(const T\&) const | Lekérdező metódus helykitöltő. |

## Lásd még

* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)