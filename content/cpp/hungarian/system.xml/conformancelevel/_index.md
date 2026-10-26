---
title: ConformanceLevel
second_title: Aspose.Slides C++ API referencia
description: Megadja a bemeneti vagy kimeneti ellenőrzés mértékét, amelyet az XmlReader és XmlWriter objektumok végeznek.
type: docs
weight: 625
url: /hu/system.xml/conformancelevel/
---
## ConformanceLevel enum

Meghatározza a bemenet vagy kimenet ellenőrzésének mértékét, amelyet a [XmlReader](../xmlreader/) és [XmlWriter](../xmlwriter/) objektumok végrehajtanak.

```cpp
enum class ConformanceLevel
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Auto | 0 | A [XmlReader](../xmlreader/) vagy [XmlWriter](../xmlwriter/) objektum automatikusan felismeri, hogy dokumentumszintű vagy fragmentumszintű ellenőrzést kell-e végrehajtani, és a megfelelő ellenőrzést végzi. Ha egy másik [XmlReader](../xmlreader/) vagy [XmlWriter](../xmlwriter/) objektumot csomagolsz, a külső objektum nem végez további megfelelőségi ellenőrzést. A megfelelőségi ellenőrzés a mögöttes objektumra marad. |
| Fragment | 1 | Az XML adat egy [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), ahogyan azt a W3C definiálja. Ez a megfelelőségi szint egy olyan XML dokumentumot jelöl, amelynek nincs gyökérelem, de egyébként jól formázott. Ez a ellenőrzési szint biztosítja, hogy a beolvasott vagy írt adatfolyam bármely feldolgozó által mint egy [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) felhasználható legyen. |
| Document | 2 | Az XML adat megfelel a W3C által definiált jól formázott [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) szabályainak. Ez a ellenőrzési szint biztosítja, hogy a beolvasott vagy írt adatfolyam bármely feldolgozó által [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed)ként felhasználható legyen. |

## Lásd még

* Névterület [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)