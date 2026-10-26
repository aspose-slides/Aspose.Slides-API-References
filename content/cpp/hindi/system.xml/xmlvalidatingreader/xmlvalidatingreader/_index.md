---
title: XmlValidatingReader()
second_title: Aspose.Slides के C++ API संदर्भ
description: दिए गए XmlReader से प्राप्त सामग्री को मान्य करने वाले XmlValidatingReader क्लास का नया उदाहरण आरंभ करता है।
type: docs
weight: 430
url: /hi/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor


दिए गए [XmlReader](../../xmlreader/) से प्राप्त सामग्री को मान्य करने वाले [XmlValidatingReader](../) क्लास का नया उदाहरण प्रारंभ करता है।

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | वैलिडेशन के दौरान पढ़ने के लिए [XmlReader](../../xmlreader/)। वर्तमान कार्यान्वयन केवल [XmlTextReader](../../xmltextreader/) का समर्थन करता है। |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


निर्दिष्ट मानों के साथ [XmlValidatingReader](../) क्लास का नया उदाहरण प्रारंभ करता है।

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | XML फ्रैगमेंट को पार्स करने वाली स्ट्रिंग। |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML फ्रैगमेंट का XmlNodeType। यह यह भी निर्धारित करता है कि फ्रैगमेंट स्ट्रिंग में क्या हो सकता है (नीचे तालिका देखें)। |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML फ्रैगमेंट को पार्स करने के लिए [XmlParserContext](../../xmlparsercontext/)। इसमें उपयोग करने के लिए [NameTable](../../nametable/), एन्कोडिंग, नेमस्पेस स्कोप, वर्तमान **xml:lang**, और **xml:space** स्कोप शामिल है। |

## टिप्पणियाँ



निम्न तालिका **fragType** के मान्य मानों और विभिन्न नोड प्रकारों को रीडर कैसे पार्स करता है, को दर्शाती है।

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| Any valid element content (for example, any combination of elements, comments, processing instructions, cdata, text, and entity references). |
| [Attribute](../../../system/attribute/)| The value of an attribute (the part inside the quotes). |
| Document| The contents of an entire XML document; this enforces document level rules. |


## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


निर्दिष्ट मानों के साथ [XmlValidatingReader](../) क्लास का नया उदाहरण प्रारंभ करता है।

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML फ्रैगमेंट को पार्स करने वाली स्ट्रीम। |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML फ्रैगमेंट का XmlNodeType। यह यह निर्धारित करता है कि फ्रैगमेंट में क्या हो सकता है (नीचे तालिका देखें)। |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML फ्रैगमेंट को पार्स करने के लिए [XmlParserContext](../../xmlparsercontext/)। इसमें उपयोग करने के लिए [XmlNameTable](../../xmlnametable/), एन्कोडिंग, नेमस्पेस स्कोप, वर्तमान **xml:lang**, और **xml:space** स्कोप शामिल है। |

## टिप्पणियाँ



निम्न तालिका **fragType** के मान्य मानों और विभिन्न नोड प्रकारों को रीडर कैसे पार्स करता है, को दर्शाती है।

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| Any valid element content (for example, any combination of elements, comments, processing instructions, cdata, text, and entity references). |
| [Attribute](../../../system/attribute/)| The value of an attribute (the part inside the quotes). |
| Document| The contents of an entire XML document; this enforces document level rules. |


## See Also

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)