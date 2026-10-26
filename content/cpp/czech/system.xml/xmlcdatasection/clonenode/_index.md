---
title: CloneNode()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří duplikát tohoto uzlu.
type: docs
weight: 53
url: /cs/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) metoda


Vytvoří duplikát tohoto uzlu.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** pro rekurzivní klonování podstromu pod zadaným uzlem; **false** pro klonování pouze samotného uzlu. Protože CDATA uzly nemají žádné potomky, bez ohledu na nastavení parametru bude klonovaný uzel vždy obsahovat datový obsah. |

### Návratová hodnota

Klonovaný uzel.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlCDataSection](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)