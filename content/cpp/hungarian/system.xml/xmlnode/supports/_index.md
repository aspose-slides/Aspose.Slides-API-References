---
title: Supports()
second_title: Aspose.Slides C++ API-referencia
description: Megvizsgálja, hogy a DOM megvalósítás egy adott funkciót támogat-e.
type: docs
weight: 482
url: /hu/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) metódus

Megvizsgálja, hogy a DOM megvalósítás egy adott funkciót támogat-e.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| feature | [String](../../../system/string/) | A tesztelendő funkció csomagneve. Ez a név nem kis- és nagybetű érzékeny. |
| version | [String](../../../system/string/) | A tesztelendő csomagnev verziószáma. Ha a verzió nincs megadva (null), akkor a funkció bármely verziójának támogatása azt eredményezi, hogy a metódus **true** értéket ad vissza. |

### Visszatérési érték

**true** ha a funkció a megadott verzióban meg van valósítva; egyébként **false**.

## Megjegyzés

Az alábbi táblázat leírja a **true** értéket visszaadó kombinációkat.

| Funkció | [Version](../../../system/version/) |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNode](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)