---
title: HasFeature()
second_title: Aspose.Slides for C++ API referenciája
description: Megvizsgálja, hogy a Dokumentum Objektum Modell (DOM) megvalósítás tartalmaz-e egy adott funkciót.
type: docs
weight: 14
url: /hu/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String&, const String&) metódus

Megvizsgálja, hogy a [Object](../../../system/object/) Dokumentum Modell (DOM) megvalósítás tartalmaz-e egy adott funkciót.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | A vizsgálandó funkció csomagnév. Ez a név nem kis- és nagybetű érzékeny. |
| strVersion | const [String](../../../system/string/)\& | Ennek a csomagnévnek a verziószáma. Ha a verzió nincs megadva (**nullptr**), akkor a funkció bármely verziójának támogatása azt eredményezi, hogy a metódus **true** értéket ad vissza. |

### Visszatérési érték

**true** ha a funkció a megadott verzióban implementálva van; egyébként **false**.

## Megjegyzések

Az alábbi táblázat mutatja azokat a kombinációkat, amelyek esetén a **HasFeature** **true** értéket ad vissza.

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlImplementation](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)