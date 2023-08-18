---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Moves to the attribute with the specified name.
type: docs
weight: 300
url: /system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) method


Moves to the attribute with the specified name.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the attribute. |

### Return Value

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlNodeReader::MoveToAttribute(String, String) method


Moves to the attribute with the specified local name and namespace URI.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The local name of the attribute. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute. |

### Return Value

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlNodeReader::MoveToAttribute(int32_t) method


Moves to the attribute with the specified index.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| attributeIndex | **int32_t** | The index of the attribute. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)