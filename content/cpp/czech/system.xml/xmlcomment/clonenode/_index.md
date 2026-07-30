---
title: CloneNode()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří duplikát tohoto uzlu.
type: docs
weight: 40
url: /cs/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) metoda

Vytvoří duplikát tohoto uzlu.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| deep | **bool** | **true** pro rekurzivní klonování podstromu pod zadaným uzlem; **false** pro klonování pouze samotného uzlu. Protože uzly komentáře nemají potomky, duplikovaný uzel vždy obsahuje textový obsah, bez ohledu na nastavení parametru. |

### Návratová hodnota

Duplikovaný uzel.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlComment](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)