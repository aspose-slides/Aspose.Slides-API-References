---
title: PrependChild()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Přidá zadaný uzel na začátek seznamu poduzlů tohoto uzlu.
type: docs
weight: 261
url: /cs/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) metoda

Přidá zadaný uzel na začátek seznamu poduzlů tohoto uzlu.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) k přidání. Pokud je to [XmlDocumentFragment](../../xmldocumentfragment/), celý obsah fragmentu dokumentu je přesunut do seznamu poduzlů tohoto uzlu. |

### Návratová hodnota

Přidaný [XmlNode](../../xmlnode/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlAttribute](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)