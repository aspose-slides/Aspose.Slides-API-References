---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Moves to the attribute with the specified name.
type: docs
weight: 508
url: /system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) method


Moves to the attribute with the specified name.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the attribute. |

### Return Value

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlTextReader::MoveToAttribute(String, String) method


Moves to the attribute with the specified local name and namespace URI.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute. |

### Return Value

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlTextReader::MoveToAttribute(int32_t) method


Moves to the attribute with the specified index.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | The index of the attribute. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)