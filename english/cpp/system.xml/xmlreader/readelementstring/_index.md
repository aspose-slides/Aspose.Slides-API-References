---
title: ReadElementString()
second_title: Aspose.Slides for C++ API Reference
description: "Reads a text-only element. However, it is recommended to use the XmlReader::ReadElementContentAsString method instead, because it provides a more straightforward way to handle this operation."
type: docs
weight: 859
url: /cpp/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() method


Reads a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```


### Return Value

The text contained in the element that was read. An empty string if the element is empty.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlReader::ReadElementString([String](../../../system/string/)) method


Checks that the [XmlReader::get_Name](../get_name/) value of the element found matches the given string before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The name to check. |

### Return Value

The text contained in the element that was read. An empty string if the element is empty.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlReader::ReadElementString([String](../../../system/string/), [String](../../../system/string/)) method


Checks that the [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values of the element found matches the given strings before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | The local name to check. |
| ns | [String](../../../system/string/) | The namespace URI to check. |

### Return Value

The text contained in the element that was read. An empty string if the element is empty.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
