---
title: GetAttribute()
second_title: Aspose.Slides for C++ API Reference
description: "When overridden in a derived class, gets the value of the attribute with the specified XmlReader::get_Name value."
type: docs
weight: 599
url: /system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) method


When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_Name](../get_name/) value.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the attribute. |

### Return Value

The value of the specified attribute. If the attribute is not found or the value is [String::Empty](../../../system/string/empty/), **nullptr** is returned.

## XmlReader::GetAttribute(String, String) method


When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The local name of the attribute. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute. |

### Return Value

The value of the specified attribute. If the attribute is not found or the value is [String::Empty](../../../system/string/empty/), **nullptr** is returned. This method does not move the reader.

## XmlReader::GetAttribute(int32_t) method


When overridden in a derived class, gets the value of the attribute with the specified index.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | The index of the attribute. The index is zero-based. (The first attribute has index 0.) |

### Return Value

The value of the specified attribute. This method does not move the reader.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)