---
title: CloneNode()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří duplikát tohoto uzlu.
type: docs
weight: 157
url: /cs/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) metoda

Vytvoří duplikát tohoto uzlu.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| deep | **bool** | **true** pro rekurzivní klonování podstromu pod zadaným uzlem; **false** pro klonování pouze samotného uzlu. Protože [XmlDeclaration](../) uzly nemají potomky, zklonovaný uzel vždy zahrnuje datovou hodnotu, bez ohledu na nastavení parametru. |

## Návratová hodnota

Zklonovaný uzel.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [XmlNode](../../xmlnode/)
* třída [XmlDeclaration](../)
* jmenný prostor [System::Xml](../../)
* knihovna [Aspose.Slides](../../../)