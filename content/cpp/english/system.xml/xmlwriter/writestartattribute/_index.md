---
title: WriteStartAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Writes the start of an attribute with the specified local name and namespace URI.
type: docs
weight: 144
url: /system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String&, const String&) method


Writes the start of an attribute with the specified local name and namespace URI.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | The local name of the attribute. |
| ns | const [String](../../../system/string/)& | The namespace URI of the attribute. |

### Exceptions

| Exception | Description |
| --- | --- |
| EncoderFallbackException | There is a character in the buffer that is a valid XML character but is not valid for the output encoding. For example, if the output encoding is ASCII, you should only use characters from the range of 0 to 127 for element and attribute names. The invalid character might be in the argument of this method or in an argument of previous methods that were writing to the buffer. Such characters are escaped by character entity references when possible (for example, in text nodes or attribute values). However, the character entity reference is not allowed in element and attribute names, comments, processing instructions, or CDATA sections. |


## XmlWriter::WriteStartAttribute(const String&, const String&, const String&) method


When overridden in a derived class, writes the start of an attribute with the specified prefix, local name, and namespace URI.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)& | The namespace prefix of the attribute. |
| localName | const [String](../../../system/string/)& | The local name of the attribute. |
| ns | const [String](../../../system/string/)& | The namespace URI for the attribute. |

### Exceptions

| Exception | Description |
| --- | --- |
| EncoderFallbackException | There is a character in the buffer that is a valid XML character but is not valid for the output encoding. For example, if the output encoding is ASCII, you should only use characters from the range of 0 to 127 for element and attribute names. The invalid character might be in the argument of this method or in an argument of previous methods that were writing to the buffer. Such characters are escaped by character entity references when possible (for example, in text nodes or attribute values). However, the character entity reference is not allowed in element and attribute names, comments, processing instructions, or CDATA sections. |


## XmlWriter::WriteStartAttribute(const String&) method


Writes the start of an attribute with the specified local name.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | The local name of the attribute. |

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