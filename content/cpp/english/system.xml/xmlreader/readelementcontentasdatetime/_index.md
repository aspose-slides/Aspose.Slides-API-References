---
title: ReadElementContentAsDateTime()
second_title: Aspose.Slides for C++ API Reference
description: Reads the current element and returns the contents as a DateTime object.
type: docs
weight: 495
url: /system.xml/xmlreader/readelementcontentasdatetime/
---
## XmlReader::ReadElementContentAsDateTime() method


Reads the current element and returns the contents as a [DateTime](../../../system/datetime/) object.

```cpp
virtual DateTime System::Xml::XmlReader::ReadElementContentAsDateTime()
```


### Return Value

The element content as a [DateTime](../../../system/datetime/) object.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The [XmlReader](../) is not positioned on an element. |
| XmlException | The current element contains child elements. The element content cannot be converted to a [DateTime](../../../system/datetime/) object. |
| ArgumentNullException | The method is called with **nullptr** arguments. |


## XmlReader::ReadElementContentAsDateTime(String, String) method


Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [DateTime](../../../system/datetime/) object.

```cpp
virtual DateTime System::Xml::XmlReader::ReadElementContentAsDateTime(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |

### Return Value

The element contents as a [DateTime](../../../system/datetime/) object.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The [XmlReader](../) is not positioned on an element. |
| XmlException | The current element contains child elements. The element content cannot be converted to the requested type. |
| ArgumentNullException | The method is called with **nullptr** arguments. |
| ArgumentException | The specified local name and namespace URI do not match that of the current element being read. |


## See Also

* Class [DateTime](../../../system/datetime/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)