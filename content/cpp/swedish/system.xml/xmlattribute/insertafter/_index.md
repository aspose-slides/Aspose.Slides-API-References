---
title: InsertAfter()
second_title: Aspose.Slides för C++ API-referens
description: Infogar den angivna noden omedelbart efter den angivna referensnoden.
type: docs
weight: 222
url: /sv/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) method

Infogar den angivna noden omedelbart efter den angivna referensnoden.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Den [XmlNode](../../xmlnode/) att infoga. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Den [XmlNode](../../xmlnode/) som är referensnoden. **newChild** placeras efter **refChild**. |

### Returvärde

Den [XmlNode](../../xmlnode/) infogades.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlAttribute](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)