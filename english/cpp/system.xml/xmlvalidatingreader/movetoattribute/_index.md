---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Moves to the attribute with the specified name.
type: docs
weight: 456
url: /cpp/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute([String](../../../system/string/)) method


Moves to the attribute with the specified name.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the attribute. |

### Return Value

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## See Also

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlValidatingReader::MoveToAttribute([String](../../../system/string/), [String](../../../system/string/)) method


Moves to the attribute with the specified local name and namespace Uniform Resource Identifier (URI).

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute. |

### Return Value

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## See Also

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlValidatingReader::MoveToAttribute(**int32_t**) method


Moves to the attribute with the specified index.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | The index of the attribute. |

## See Also

* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
