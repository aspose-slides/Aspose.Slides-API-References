---
title: idx_get()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, gets the value of the attribute with the specified index.
type: docs
weight: 612
url: /cpp/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) method


When overridden in a derived class, gets the value of the attribute with the specified index.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | The index of the attribute. |

### Return Value

The value of the specified attribute.

## XmlReader::idx_get(String) method


When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_Name](../get_name/) value.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the attribute. |

### Return Value

The value of the specified attribute. If the attribute is not found, **nullptr** is returned.

## XmlReader::idx_get(String, String) method


When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
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
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)