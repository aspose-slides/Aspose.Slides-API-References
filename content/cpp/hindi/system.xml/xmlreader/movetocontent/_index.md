---
title: MoveToContent()
second_title: Aspose.Slides for C++ API संदर्भ
description: "जाँचता है कि वर्तमान नोड एक कंटेंट (गैर-श्वेत स्थान पाठ, CDATA, Element, EndElement, EntityReference, या EndEntity) नोड है या नहीं। यदि नोड कंटेंट नोड नहीं है, तो रीडर अगली कंटेंट नोड या फ़ाइल के अंत तक आगे बढ़ जाता है। यह निम्न प्रकार के नोड्स को छोड़ देता है: ProcessingInstruction, DocumentType, Comment, Whitespace, या SignificantWhitespace।"
type: docs
weight: 833
url: /hi/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() मेथड


जाँचता है कि वर्तमान नोड एक कंटेंट (गैर-श्वेत स्थान पाठ, **CDATA**, **Element**, **EndElement**, **EntityReference**, या **EndEntity**) नोड है या नहीं। यदि नोड कंटेंट नोड नहीं है, तो रीडर अगली कंटेंट नोड या फ़ाइल के अंत तक आगे बढ़ जाता है। यह निम्न प्रकार के नोड्स को छोड़ देता है: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, या **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### रिटर्न वैल्यू

विधि द्वारा पाए गए वर्तमान नोड का [XmlReader::get_NodeType](../get_nodetype/) मान या [XmlNodeType::None](../../xmlnodetype/) यदि रीडर ने इनपुट स्ट्रीम का अंत पहुँच लिया हो।

## संबंधित देखें

* Enum [XmlNodeType](../../xmlnodetype/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)