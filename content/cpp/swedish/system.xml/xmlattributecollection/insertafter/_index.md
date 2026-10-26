---
title: InsertAfter()
second_title: Aspose.Slides för C++ API-referens
description: Infogar det angivna attributet omedelbart efter det angivna referensattributet.
type: docs
weight: 66
url: /sv/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) metod

Infogar det angivna attributet omedelbart efter det angivna referensattributet.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | Attributet som ska infogas. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | Referensattributet. **newNode** placeras efter **refNode**. |

### Returvärde

Den [XmlAttribute](../../xmlattribute/) att infoga i samlingen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlAttribute](../../xmlattribute/)
* Klass [XmlAttributeCollection](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)