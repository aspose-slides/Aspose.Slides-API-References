---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API Reference
description: "When overridden in a derived class, moves to the attribute with the specified XmlReader::get_Name value."
type: docs
weight: 625
url: /system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) method


When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_Name](../get_name/) value.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the attribute. |

### Return Value

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | The parameter is an empty string. |


## XmlReader::MoveToAttribute(String, String) method


When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The local name of the attribute. |
| ns | [String](../../../system/string/) | The namespace URI of the attribute. |

### Return Value

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | Both parameter values are **nullptr**. |


## XmlReader::MoveToAttribute(int32_t) method


When overridden in a derived class, moves to the attribute with the specified index.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | The index of the attribute. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentOutOfRangeException | The parameter has a negative value. |


## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)