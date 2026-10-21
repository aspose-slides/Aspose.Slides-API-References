---
title: ImportNode()
second_title: Aspose.Slides for C++ API Reference
description: Imports a node from another document to the current document.
type: docs
weight: 469
url: /system.xml/xmldocument/importnode/
---
## XmlDocument::ImportNode(SharedPtr\<XmlNode\>, bool) method


Imports a node from another document to the current document.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ImportNode(SharedPtr<XmlNode> node, bool deep)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | The node being imported. |
| deep | **bool** | **true** to perform a deep clone; otherwise, **false**. |

### Return Value

The imported [XmlNode](../../xmlnode/).

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | Calling this method on a node type which cannot be imported. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)