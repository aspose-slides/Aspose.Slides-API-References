---
title: CloneNode()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří duplikát tohoto uzlu. Notation uzly nelze klonovat. Volání této metody na objektu typu XmlNotation vyvolá výjimku.
type: docs
weight: 118
url: /cs/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) metoda


Vytvoří duplikát tohoto uzlu. Notation uzly nelze klonovat. Volání této metody na objektu typu [XmlNotation](../) vyvolá výjimku.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| deep | **bool** | **true** k rekurzivnímu klonování podstromu pod zadaným uzlem; **false** k klonování jen samotného uzlu. |

### Návratová hodnota

[XmlNode](../../xmlnode/) kopie uzlu, ze kterého je metoda volána.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlNotation](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)