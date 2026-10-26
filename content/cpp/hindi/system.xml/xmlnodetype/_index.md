---
title: XmlNodeType
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: नोड के प्रकार को निर्दिष्ट करता है।
type: docs
weight: 833
url: /hi/system.xml/xmlnodetype/
---
## XmlNodeType enum

नोड के प्रकार को निर्दिष्ट करता है।

```cpp
enum class XmlNodeType
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| None | 0 | यह [XmlReader](../xmlreader/) द्वारा वापस किया जाता है यदि एक **Read** मेथड को बुलाया नहीं गया है। |
| Element | 1 | एक तत्व (उदाहरण के लिए, **<item>**). |
| Attribute | 2 | एक विशेषता (उदाहरण के लिए, **id='123'**). |
| Text | 3 | एक नोड की पाठ सामग्री। एक [XmlNodeType::Text](./) नोड के कोई चाइल्ड नोड नहीं हो सकते। यह [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) और [XmlNodeType::EntityReference](./) नोड्स के चाइल्ड नोड के रूप में प्रकट हो सकता है। |
| CDATA | 4 | एक CDATA सेक्शन (उदाहरण के लिए, **my escaped text**). |
| EntityReference | 5 | एक एंटिटी का संदर्भ (उदाहरण के लिए, **&num;**). |
| Entity | 6 | एक एंटिटी घोषणा (उदाहरण के लिए, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | एक प्रोसेसिंग इंस्ट्रक्शन (उदाहरण के लिए, **<?pi test?>**). |
| Comment | 8 | एक टिप्पणी (उदाहरण के लिए, ****). |
| Document | 9 | एक दस्तावेज़ ऑब्जेक्ट जो दस्तावेज़ ट्री की जड़ के रूप में पूरी XML दस्तावेज़ तक पहुँच प्रदान करता है। |
| DocumentType | 10 | दस्तावेज़ प्रकार घोषणा, जो निम्न टैग द्वारा दर्शायी जाती है (उदाहरण के लिए, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | एक दस्तावेज़ फ्रैगमेंट। |
| Notation | 12 | दस्तावेज़ प्रकार घोषणा में एक नोटेशन (उदाहरण के लिए, **<!NOTATION...>**). |
| Whitespace | 13 | मार्कअप के बीच का रिक्त स्थान। |
| SignificantWhitespace | 14 | मिश्रित कंटेंट मॉडल में मार्कअप के बीच का रिक्त स्थान या **xml:space=\"preserve\"** स्कोप के भीतर का रिक्त स्थान। |
| EndElement | 15 | एक एंड एलिमेंट टैग (उदाहरण के लिए, ****). |
| EndEntity | 16 | जब [XmlReader](../xmlreader/) [XmlReader::ResolveEntity](../xmlreader/resolveentity/) को कॉल करने के परिणामस्वरूप एंटिटी रिप्लेसमेंट के अंत तक पहुँचता है तो वापस किया जाता है। |
| XmlDeclaration | 17 | XML घोषणा (उदाहरण के लिए, **<?xml version='1.0'?>**). [XmlNodeType::XmlDeclaration](./) नोड को दस्तावेज़ में पहला नोड होना चाहिए। इसमें चाइल्ड नहीं हो सकते। यह [XmlNodeType::Document](./) नोड का चाइल्ड है। इसमें ऐसे विशेषताएँ हो सकती हैं जो संस्करण और एन्कोडिंग जानकारी प्रदान करती हैं। |

## देखें

* नामस्थान [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)