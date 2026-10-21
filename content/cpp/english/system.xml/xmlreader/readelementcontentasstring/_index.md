---
title: ReadElementContentAsString()
second_title: Aspose.Slides for C++ API Reference
description: Reads the current element and returns the contents as a String object.
type: docs
weight: 573
url: /system.xml/xmlreader/readelementcontentasstring/
---
## XmlReader::ReadElementContentAsString() method


Reads the current element and returns the contents as a [String](../../../system/string/) object.

```cpp
virtual String System::Xml::XmlReader::ReadElementContentAsString()
```


### Return Value

The element content as a [String](../../../system/string/) object.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The [XmlReader](../) is not positioned on an element. |
| XmlException | The current element contains child elements. The element content cannot be converted to a [String](../../../system/string/) object. |
| ArgumentNullException | The method is called with **nullptr** arguments. |


## XmlReader::ReadElementContentAsString(String, String) method


Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [String](../../../system/string/) object.

```cpp
virtual String System::Xml::XmlReader::ReadElementContentAsString(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |

### Return Value

The element content as a [String](../../../system/string/) object.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The [XmlReader](../) is not positioned on an element. |
| XmlException | The current element contains child elements. The element content cannot be converted to a [String](../../../system/string/) object. |
| ArgumentNullException | The method is called with **nullptr** arguments. |
| ArgumentException | The specified local name and namespace URI do not match that of the current element being read. |


## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)