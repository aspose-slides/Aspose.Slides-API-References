---
title: GetAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Returns the value of the attribute with the specified name.
type: docs
weight: 443
url: /system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) method


Returns the value of the attribute with the specified name.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the attribute. |

### Return Value

The value of the specified attribute. If the attribute is not found, **nullptr** is returned.

## XmlValidatingReader::GetAttribute(String, String) method


Returns the value of the attribute with the specified local name and namespace Uniform Resource Identifier (URI).

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute. |

### Return Value

The value of the specified attribute. If the attribute is not found, **nullptr** is returned. This method does not move the reader.

## XmlValidatingReader::GetAttribute(int32_t) method


Returns the value of the attribute with the specified index.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | The index of the attribute. The index is zero-based. (The first attribute has index 0.) |

### Return Value

The value of the specified attribute.

## See Also

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)