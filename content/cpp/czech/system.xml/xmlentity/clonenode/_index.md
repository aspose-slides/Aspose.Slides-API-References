---
title: CloneNode()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří duplikát tohoto uzlu. Uzly typu Entity nelze klonovat. Volání této metody na objektu XmlEntity vyvolá výjimku.
type: docs
weight: 170
url: /cs/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) metoda

Vytvoří duplikát tohoto uzlu. Uzly typu Entity nelze klonovat. Volání této metody na objektu typu [XmlEntity](../) vyvolá výjimku.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| deep | **bool** | **true** pro rekurzivní klonování podstromu pod zadaným uzlem; **false** pro klonování pouze samotného uzlu. |

### Návratová hodnota

Kopie [XmlNode](../../xmlnode/), ze které je metoda volána.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntity](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)