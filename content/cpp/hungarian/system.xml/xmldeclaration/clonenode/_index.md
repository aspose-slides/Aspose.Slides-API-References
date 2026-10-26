---
title: CloneNode()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza ennek a csomópontnak a másolatát.
type: docs
weight: 157
url: /hu/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) metódus


Létrehozza ennek a csomópontnak a másolatát.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deep | **bool** | **true** a megadott csomópont alatti részfa rekurzív klónozásához; **false** csak a csomópont klónozásához. Mivel a [XmlDeclaration](../) csomópontoknak nincsenek gyermekei, a klónozott csomópont mindig tartalmazza az adatértéket, a paraméter beállításától függetlenül. |

### Visszatérési érték

A klónozott csomópont.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlDeclaration](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)