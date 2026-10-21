---
title: ReadElementContentAsDouble()
second_title: Aspose.Slides for C++ API Reference
description: Reads the current element and returns the contents as a double-precision floating-point number.
type: docs
weight: 508
url: /system.xml/xmlreader/readelementcontentasdouble/
---
## XmlReader::ReadElementContentAsDouble() method


Reads the current element and returns the contents as a double-precision floating-point number.

```cpp
virtual double System::Xml::XmlReader::ReadElementContentAsDouble()
```


### Return Value

The element content as a double-precision floating-point number.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The [XmlReader](../) is not positioned on an element. |
| XmlException | The current element contains child elements. The element content cannot be converted to a double-precision floating-point number. |
| ArgumentNullException | The method is called with **nullptr** arguments. |


## XmlReader::ReadElementContentAsDouble(String, String) method


Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a double-precision floating-point number.

```cpp
virtual double System::Xml::XmlReader::ReadElementContentAsDouble(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |

### Return Value

The element content as a double-precision floating-point number.

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