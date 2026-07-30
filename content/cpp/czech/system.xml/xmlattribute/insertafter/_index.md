---
title: InsertAfter()
second_title: Aspose.Slides pro C++ – reference API
description: Vloží zadaný uzel ihned za zadaný referenční uzel.
type: docs
weight: 222
url: /cs/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) method


Vloží zadaný uzel ihned za zadaný referenční uzel.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) k vložení. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/), který je referenční uzel. **newChild** je umístěn za **refChild**. |

### Návratová hodnota

Vložený [XmlNode](../../xmlnode/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlAttribute](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)