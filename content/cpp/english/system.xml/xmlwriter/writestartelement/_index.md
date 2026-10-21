---
title: WriteStartElement()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, writes the specified start tag and associates it with the given namespace.
type: docs
weight: 92
url: /system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String&, const String&) method


When overridden in a derived class, writes the specified start tag and associates it with the given namespace.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | The local name of the element. |
| ns | const [String](../../../system/string/)& | The namespace URI to associate with the element. If this namespace is already in scope and has an associated prefix, the writer automatically writes that prefix also. |

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The writer is closed. |
| EncoderFallbackException | There is a character in the buffer that is a valid XML character but is not valid for the output encoding. For example, if the output encoding is ASCII, you should only use characters from the range of 0 to 127 for element and attribute names. The invalid character might be in the argument of this method or in an argument of previous methods that were writing to the buffer. Such characters are escaped by character entity references when possible (for example, in text nodes or attribute values). However, the character entity reference is not allowed in element and attribute names, comments, processing instructions, or CDATA sections. |


## XmlWriter::WriteStartElement(const String&, const String&, const String&) method


When overridden in a derived class, writes the specified start tag and associates it with the given namespace and prefix.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)& | The namespace prefix of the element. |
| localName | const [String](../../../system/string/)& | The local name of the element. |
| ns | const [String](../../../system/string/)& | The namespace URI to associate with the element. |

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The writer is closed. |
| EncoderFallbackException | There is a character in the buffer that is a valid XML character but is not valid for the output encoding. For example, if the output encoding is ASCII, you should only use characters from the range of 0 to 127 for element and attribute names. The invalid character might be in the argument of this method or in an argument of previous methods that were writing to the buffer. Such characters are escaped by character entity references when possible (for example, in text nodes or attribute values). However, the character entity reference is not allowed in element and attribute names, comments, processing instructions, or CDATA sections. |


## XmlWriter::WriteStartElement(const String&) method


When overridden in a derived class, writes out a start tag with the specified local name.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | The local name of the element. |

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The writer is closed. |
| EncoderFallbackException | There is a character in the buffer that is a valid XML character but is not valid for the output encoding. For example, if the output encoding is ASCII, you should only use characters from the range of 0 to 127 for element and attribute names. The invalid character might be in the argument of this method or in an argument of previous methods that were writing to the buffer. Such characters are escaped by character entity references when possible (for example, in text nodes or attribute values). However, the character entity reference is not allowed in element and attribute names, comments, processing instructions, or CDATA sections. |


## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)