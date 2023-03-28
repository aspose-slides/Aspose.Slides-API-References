---
title: idx_get()
second_title: Aspose.Slides for C++ API Reference
description: Returns the attribute with the specified index.
type: docs
weight: 1
url: /cpp/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(**int32_t**) method


Returns the attribute with the specified index.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | The index of the attribute. |

### Return Value

The attribute at the specified index.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlAttributeCollection::idx_get(const [String](../../../system/string/)\&) method


Returns the attribute with the specified name.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | The qualified name of the attribute. |

### Return Value

The attribute with the specified name. If the attribute does not exist, this method returns **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlAttributeCollection::idx_get(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&) method


Returns the attribute with the specified local name and namespace Uniform Resource Identifier (URI).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | The local name of the attribute. |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI of the attribute. |

### Return Value

The attribute with the specified local name and namespace URI. If the attribute does not exist, this method returns **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
