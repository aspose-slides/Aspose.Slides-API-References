---
title: ReadElementContentAsObject()
second_title: Aspose.Slides for C++ API Reference
description: Reads the current element and returns the contents as an Object.
type: docs
weight: 469
url: /system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() method


Reads the current element and returns the contents as an [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```


### Return Value

A boxed object of the most appropriate type. The [XmlReader::get_ValueType](../get_valuetype/) value determines the appropriate type. If the content is typed as a list type, this method returns an array of boxed objects of the appropriate type.

## XmlReader::ReadElementContentAsObject(String, String) method


Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as an [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |

### Return Value

A boxed object of the most appropriate type. The [XmlReader::get_ValueType](../get_valuetype/) value determines the appropriate type. If the content is typed as a list type, this method returns an array of boxed objects of the appropriate type.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)