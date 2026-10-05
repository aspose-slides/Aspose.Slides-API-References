---
title: ReadElementContentAsLong()
second_title: Aspose.Slides for C++ API Reference
description: Reads the current element and returns the contents as a 64-bit signed integer.
type: docs
weight: 560
url: /system.xml/xmlreader/readelementcontentaslong/
---
## XmlReader::ReadElementContentAsLong() method


Reads the current element and returns the contents as a 64-bit signed integer.

```cpp
virtual int64_t System::Xml::XmlReader::ReadElementContentAsLong()
```


### Return Value

The element content as a 64-bit signed integer.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The [XmlReader](../) is not positioned on an element. |
| XmlException | The current element contains child elements. The element content cannot be converted to a 64-bit signed integer. |
| ArgumentNullException | The method is called with **nullptr** arguments. |


## XmlReader::ReadElementContentAsLong(String, String) method


Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a 64-bit signed integer.

```cpp
virtual int64_t System::Xml::XmlReader::ReadElementContentAsLong(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |

### Return Value

The element content as a 64-bit signed integer.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The [XmlReader](../) is not positioned on an element. |
| XmlException | The current element contains child elements. The element content cannot be converted to a 64-bit signed integer. |
| ArgumentNullException | The method is called with **nullptr** arguments. |
| ArgumentException | The specified local name and namespace URI do not match that of the current element being read. |


## See Also

* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)