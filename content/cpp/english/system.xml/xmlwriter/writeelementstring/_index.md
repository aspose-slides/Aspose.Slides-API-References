---
title: WriteElementString()
second_title: Aspose.Slides for C++ API Reference
description: Writes an element with the specified local name and value.
type: docs
weight: 443
url: /system.xml/xmlwriter/writeelementstring/
---
## XmlWriter::WriteElementString(const String&, const String&) method


Writes an element with the specified local name and value.

```cpp
void System::Xml::XmlWriter::WriteElementString(const String &localName, const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | The local name of the element. |
| value | const [String](../../../system/string/)& | The value of the element. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | The **localName** value is **nullptr** or an empty string. or The parameter values are not valid. |
| EncoderFallbackException | There is a character in the buffer that is a valid XML character but is not valid for the output encoding. For example, if the output encoding is ASCII, you should only use characters from the range of 0 to 127 for element and attribute names. The invalid character might be in the argument of this method or in an argument of previous methods that were writing to the buffer. Such characters are escaped by character entity references when possible (for example, in text nodes or attribute values). However, the character entity reference is not allowed in element and attribute names, comments, processing instructions, or CDATA sections. |


## XmlWriter::WriteElementString(const String&, const String&, const String&) method


Writes an element with the specified local name, namespace URI, and value.

```cpp
void System::Xml::XmlWriter::WriteElementString(const String &localName, const String &ns, const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | The local name of the element. |
| ns | const [String](../../../system/string/)& | The namespace URI to associate with the element. |
| value | const [String](../../../system/string/)& | The value of the element. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | The **localName** value is **nullptr** or an empty string. or The parameter values are not valid. |
| EncoderFallbackException | There is a character in the buffer that is a valid XML character but is not valid for the output encoding. For example, if the output encoding is ASCII, you should only use characters from the range of 0 to 127 for element and attribute names. The invalid character might be in the argument of this method or in an argument of previous methods that were writing to the buffer. Such characters are escaped by character entity references when possible (for example, in text nodes or attribute values). However, the character entity reference is not allowed in element and attribute names, comments, processing instructions, or CDATA sections. |


## XmlWriter::WriteElementString(const String&, const String&, const String&, const String&) method


Writes an element with the specified prefix, local name, namespace URI, and value.

```cpp
void System::Xml::XmlWriter::WriteElementString(const String &prefix, const String &localName, const String &ns, const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)& | The prefix of the element. |
| localName | const [String](../../../system/string/)& | The local name of the element. |
| ns | const [String](../../../system/string/)& | The namespace URI of the element. |
| value | const [String](../../../system/string/)& | The value of the element. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | The **localName** value is **nullptr** or an empty string. or The parameter values are not valid. |
| EncoderFallbackException | There is a character in the buffer that is a valid XML character but is not valid for the output encoding. For example, if the output encoding is ASCII, you should only use characters from the range of 0 to 127 for element and attribute names. The invalid character might be in the argument of this method or in an argument of previous methods that were writing to the buffer. Such characters are escaped by character entity references when possible (for example, in text nodes or attribute values). However, the character entity reference is not allowed in element and attribute names, comments, processing instructions, or CDATA sections. |


## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)