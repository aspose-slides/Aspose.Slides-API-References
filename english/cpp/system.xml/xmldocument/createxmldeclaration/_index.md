---
title: CreateXmlDeclaration()
second_title: Aspose.Slides for C++ API Reference
description: Creates an XmlDeclaration node with the specified values.
type: docs
weight: 378
url: /cpp/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&) method


Creates an [XmlDeclaration](../../xmldeclaration/) node with the specified values.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | The version must be \"1.0\". |
| encoding | const [String](../../../system/string/)\& | The value of the encoding attribute. This is the encoding that is used when you save the [XmlDocument](../) to a file or a stream; therefore, it must be set to a string supported by the [Text::Encoding](../../../system.text/encoding/) class, otherwise \"XmlDocument::Save(String)\" fails. If this is **nullptr** or [String::Empty](../../../system/string/empty/), the [XmlDocument::Save](../save/) method does not write an encoding attribute on the XML declaration and therefore the default encoding, UTF-8, is used. |
| standalone | const [String](../../../system/string/)\& | The value must be either \"yes\" or \"no\". If this is **nullptr** or [String::Empty](../../../system/string/empty/), the [XmlDocument::Save](../save/) method does not write a standalone attribute on the XML declaration. |

### Return Value

The new [XmlDeclaration](../../xmldeclaration/) node.
## Remarks



Note: If the [XmlDocument](../) is saved to either a TextWriter or an [XmlTextWriter](../../xmltextwriter/), this encoding value is discarded. Instead, the encoding of the TextWriter or the [XmlTextWriter](../../xmltextwriter/) is used. This ensures that the XML written out can be read back using the correct encoding. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDeclaration](../../xmldeclaration/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
