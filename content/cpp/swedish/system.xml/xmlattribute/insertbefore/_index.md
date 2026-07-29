---
title: InsertBefore()
second_title: Aspose.Slides för C++ API-referens
description: Infogar den angivna noden direkt före den angivna referensnoden.
type: docs
weight: 209
url: /sv/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) metod

Infogar den angivna noden direkt före den angivna referensnoden.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Den [XmlNode](../../xmlnode/) att infoga. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Den [XmlNode](../../xmlnode/) som är referensnoden. **newChild** placeras före denna nod. |

### Returvärde

Den [XmlNode](../../xmlnode/) som infogades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlAttribute](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)