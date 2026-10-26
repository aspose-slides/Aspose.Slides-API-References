---
title: CloneNode()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří duplikát tohoto uzlu.
type: docs
weight: 79
url: /cs/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) metoda

Vytvoří duplikát tohoto uzlu.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| deep | **bool** | **true** pro rekurzivní klonování podstromu pod zadaným uzlem; **false** pro klonování pouze samotného uzlu. Pro uzly významných bílých znaků klonovaný uzel vždy zahrnuje datovou hodnotu, bez ohledu na nastavení parametru. |

### Návratová hodnota

Klonovaný uzel.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlSignificantWhitespace](../)
* Namespace [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)