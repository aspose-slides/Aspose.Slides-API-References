---
title: InsertBefore()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vloží zadaný uzel okamžitě před zadaný referenční uzel.
type: docs
weight: 209
url: /cs/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) metoda

Vloží zadaný uzel okamžitě před zadaný referenční uzel.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) k vložení. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) je referenční uzel. **newChild** je umístěn před tímto uzlem. |

### Návratová hodnota

Vložený [XmlNode](../../xmlnode/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlAttribute](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)