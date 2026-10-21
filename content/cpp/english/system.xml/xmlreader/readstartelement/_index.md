---
title: ReadStartElement()
second_title: Aspose.Slides for C++ API Reference
description: Checks that the current node is an element and advances the reader to the next node.
type: docs
weight: 846
url: /system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() method


Checks that the current node is an element and advances the reader to the next node.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```


### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | Incorrect XML was encountered in the input stream. |


## XmlReader::ReadStartElement(String) method


Checks that the current content node is an element with the given [XmlReader::get_Name](../get_name/) value and advances the reader to the next node.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the element. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | Incorrect XML was encountered in the input stream. The [XmlReader::get_Name](../get_name/) of the element does not match the given **name**. |


## XmlReader::ReadStartElement(String, String) method


Checks that the current content node is an element with the given [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values and advances the reader to the next node.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | The local name of the element. |
| ns | [String](../../../system/string/) | The namespace URI of the element. |

### Exceptions

| Exception | Description |
| --- | --- |
| XmlException | Incorrect XML was encountered in the input stream. The [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values of the element found do not match the given arguments. |


## See Also

* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)