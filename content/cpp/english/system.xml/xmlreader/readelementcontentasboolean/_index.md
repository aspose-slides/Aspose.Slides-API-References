---
title: ReadElementContentAsBoolean()
second_title: Aspose.Slides for C++ API Reference
description: Reads the current element and returns the contents as a Boolean object.
type: docs
weight: 482
url: /system.xml/xmlreader/readelementcontentasboolean/
---
## XmlReader::ReadElementContentAsBoolean() method


Reads the current element and returns the contents as a [Boolean](../../../system/boolean/) object.

```cpp
virtual bool System::Xml::XmlReader::ReadElementContentAsBoolean()
```


### Return Value

The element content as a [Boolean](../../../system/boolean/) object.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The [XmlReader](../) is not positioned on an element. |
| XmlException | The current element contains child elements. The element content cannot be converted to a [Boolean](../../../system/boolean/) object. |
| ArgumentNullException | The method is called with **nullptr** arguments. |


## XmlReader::ReadElementContentAsBoolean(String, String) method


Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [Boolean](../../../system/boolean/) object.

```cpp
virtual bool System::Xml::XmlReader::ReadElementContentAsBoolean(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |

### Return Value

The element content as a [Boolean](../../../system/boolean/) object.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The [XmlReader](../) is not positioned on an element. |
| XmlException | The current element contains child elements. The element content cannot be converted to the requested type. |
| ArgumentNullException | The method is called with **nullptr** arguments. |
| ArgumentException | The specified local name and namespace URI do not match that of the current element being read. |


## See Also

* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)