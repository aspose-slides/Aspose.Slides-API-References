---
title: GetAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Returns the value of the attribute with the specified name.
type: docs
weight: 287
url: /cpp/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute([String](../../../system/string/)) method


Returns the value of the attribute with the specified name.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the attribute. |

### Return Value

The value of the specified attribute. If the attribute is not found, **nullptr** is returned.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlNodeReader::GetAttribute([String](../../../system/string/), [String](../../../system/string/)) method


Returns the value of the attribute with the specified local name and namespace URI.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The local name of the attribute. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute. |

### Return Value

The value of the specified attribute. If the attribute is not found, **nullptr** is returned.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlNodeReader::GetAttribute(**int32_t**) method


Returns the value of the attribute with the specified index.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| attributeIndex | **int32_t** | The index of the attribute. The index is zero-based. (The first attribute has index 0.) |

### Return Value

The value of the specified attribute.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
