---
title: InsertAfter()
second_title: Aspose.Slides for C++ API Reference
description: Inserts the specified attribute immediately after the specified reference attribute.
type: docs
weight: 66
url: /system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) method


Inserts the specified attribute immediately after the specified reference attribute.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | The attribute to insert. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | The reference attribute. **newNode** is placed after the **refNode**. |

### Return Value

The [XmlAttribute](../../xmlattribute/) to insert into the collection.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)