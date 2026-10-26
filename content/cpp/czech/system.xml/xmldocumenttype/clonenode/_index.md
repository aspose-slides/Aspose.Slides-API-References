---
title: CloneNode()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Vytvoří duplikát tohoto uzlu.
type: docs
weight: 118
url: /cs/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) metoda

Vytvoří duplikát tohoto uzlu.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| deep | **bool** | **true** pro rekurzivní klonování podstromu pod zadaným uzlem; **false** pro klonování pouze samotného uzlu. Pro uzly typu dokumentu klonovaný uzel vždy zahrnuje podstrom, bez ohledu na nastavení parametru. |

### Návratová hodnota

Klónovaný uzel.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlDocumentType](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)