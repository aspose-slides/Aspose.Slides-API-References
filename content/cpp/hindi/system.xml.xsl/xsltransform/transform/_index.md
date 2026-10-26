---
title: Transform()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट args का उपयोग करके XPathNavigator में XML डेटा को परिवर्तित करता है और परिणाम को एक XmlReader में आउटपुट करता है।
type: docs
weight: 40
url: /hi/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) मेथड


XPathNavigator में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक [XmlReader](../../../system.xml/xmlreader/) में आउटपुट करता है।

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | एक XPathNavigator जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) जो XSLT **document()** फ़ंक्शन को रेज़ॉल्व करने के लिए उपयोग किया जाता है। यदि यह **nullptr** है, तो **document()** फ़ंक्शन हल नहीं किया जाता। [XmlResolver](../../../system.xml/xmlresolver/) इस मेथड के पूरा होने के बाद कैश नहीं किया जाता। |

### वापसी मान

एक [XmlReader](../../../system.xml/xmlreader/) जिसमें परिवर्तन के परिणाम होते हैं।

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) मेथड


XPathNavigator में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक [XmlReader](../../../system.xml/xmlreader/) में आउटपुट करता है।

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | एक XPathNavigator जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |

### वापसी मान

एक [XmlReader](../../../system.xml/xmlreader/) जिसमें परिवर्तन के परिणाम होते हैं।

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) मेथड


XPathNavigator में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | एक XPathNavigator जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिससे आप आउटपुट चाहते हैं। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) जो XSLT **document()** फ़ंक्शन को रेज़ॉल्व करने के लिए उपयोग किया जाता है। यदि यह **nullptr** है, तो **document()** फ़ंक्शन हल नहीं किया जाता। [XmlResolver](../../../system.xml/xmlresolver/) इस मेथड के पूरा होने के बाद कैश नहीं किया जाता। |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) मेथड


XPathNavigator में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | एक XPathNavigator जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिससे आप आउटपुट चाहते हैं। |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) मेथड


XPathNavigator में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक Stream में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | एक XPathNavigator जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिससे आप आउटपुट चाहते हैं। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) जो XSLT **document()** फ़ंक्शन को रेज़ॉल्व करने के लिए उपयोग किया जाता है। यदि यह **nullptr** है, तो **document()** फ़ंक्शन हल नहीं किया जाता। [XmlResolver](../../../system.xml/xmlresolver/) इस मेथड के पूरा होने के बाद कैश नहीं किया जाता। |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) मेथड


XPathNavigator में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक Stream में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | एक XPathNavigator जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिससे आप आउटपुट चाहते हैं। |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) मेथड


XPathNavigator में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक TextWriter में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | एक XPathNavigator जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | वह TextWriter जिससे आप आउटपुट चाहते हैं। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) जो XSLT **document()** फ़ंक्शन को रेज़ॉल्व करने के लिए उपयोग किया जाता है। यदि यह **nullptr** है, तो **document()** फ़ंक्शन हल नहीं किया जाता। [XmlResolver](../../../system.xml/xmlresolver/) इस मेथड के पूरा होने के बाद कैश नहीं किया जाता। |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) मेथड


XPathNavigator में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक TextWriter में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | एक XPathNavigator जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | वह TextWriter जिससे आप आउटपुट चाहते हैं। |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) मेथड


IXPathNavigable में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक [XmlReader](../../../system.xml/xmlreader/) में आउटपुट करता है।

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | एक ऑब्जेक्ट जो IXPathNavigable इंटरफ़ेस को लागू करता है। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) जो XSLT **document()** फ़ंक्शन को रेज़ॉल्व करने के लिए उपयोग किया जाता है। यदि यह **nullptr** है, तो **document()** फ़ंक्शन हल नहीं किया जाता। [XmlResolver](../../../system.xml/xmlresolver/) इस मेथड के पूरा होने के बाद कैश नहीं किया जाता। |

### वापसी मान

एक [XmlReader](../../../system.xml/xmlreader/) जिसमें परिवर्तन के परिणाम होते हैं।

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) मेथड


IXPathNavigable में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक [XmlReader](../../../system.xml/xmlreader/) में आउटपुट करता है।

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | एक ऑब्जेक्ट जो IXPathNavigable इंटरफ़ेस को लागू करता है। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |

### वापसी मान

एक [XmlReader](../../../system.xml/xmlreader/) जिसमें परिवर्तन के परिणाम होते हैं।

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) मेथड


IXPathNavigable में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक TextWriter में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | एक ऑब्जेक्ट जो IXPathNavigable इंटरफ़ेस को लागू करता है। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | वह TextWriter जिससे आप आउटपुट चाहते हैं। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) जो XSLT **document()** फ़ंक्शन को रेज़ॉल्व करने के लिए उपयोग किया जाता है। यदि यह **nullptr** है, तो **document()** फ़ंक्शन हल नहीं किया जाता। [XmlResolver](../../../system.xml/xmlresolver/) इस मेथड के पूरा होने के बाद कैश नहीं किया जाता। |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) मेथड


IXPathNavigable में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक TextWriter में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | एक ऑब्जेक्ट जो IXPathNavigable इंटरफ़ेस को लागू करता है। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | वह TextWriter जिससे आप आउटपुट चाहते हैं। |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) मेथड


IXPathNavigable में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक Stream में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | एक ऑब्जेक्ट जो IXPathNavigable इंटरफ़ेस को लागू करता है। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिससे आप आउटपुट चाहते हैं। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) जो XSLT **document()** फ़ंक्शन को रेज़ॉल्व करने के लिए उपयोग किया जाता है। यदि यह **nullptr** है, तो **document()** फ़ंक्शन हल नहीं किया जाता। [XmlResolver](../../../system.xml/xmlresolver/) इस [XslTransform::Transform](./) मेथड के पूरा होने के बाद कैश नहीं किया जाता। |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) मेथड


IXPathNavigable में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक Stream में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | एक ऑब्जेक्ट जो IXPathNavigable इंटरफ़ेस को लागू करता है। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिससे आप आउटपुट चाहते हैं। |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) मेथड


IXPathNavigable में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | एक ऑब्जेक्ट जो IXPathNavigable इंटरफ़ेस को लागू करता है। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिससे आप आउटपुट चाहते हैं। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) जो XSLT **document()** फ़ंक्शन को रेज़ॉल्व करने के लिए उपयोग किया जाता है। यदि यह **nullptr** है, तो **document()** फ़ंक्शन हल नहीं किया जाता। [XmlResolver](../../../system.xml/xmlresolver/) इस मेथड के पूरा होने के बाद कैश नहीं किया जाता। |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) मेथड


IXPathNavigable में XML डेटा को निर्दिष्ट **args** का उपयोग करके परिवर्तित करता है और परिणाम को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | एक ऑब्जेक्ट जो IXPathNavigable इंटरफ़ेस को लागू करता है। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित करने के लिए डेटा है। |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो परिवर्तन के इनपुट के रूप में उपयोग होते हैं। |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिससे आप आउटपुट चाहते हैं। |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) मेथड


इनपुट फ़ाइल में XML डेटा को परिवर्तित करता है और परिणाम को आउटपुट फ़ाइल में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | परिवर्तित करने के लिए स्रोत दस्तावेज़ का URL। |
| outputfile | const [String](../../../system/string/)\& | आउटपुट फ़ाइल का URL। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) जो XSLT **document()** फ़ंक्शन को रेज़ॉल्व करने के लिए उपयोग किया जाता है। यदि यह **nullptr** है, तो **document()** फ़ंक्शन हल नहीं किया जाता। [XmlResolver](../../../system.xml/xmlresolver/) इस [XslTransform::Transform](./) मेथड के पूरा होने के बाद कैश नहीं किया जाता। |

## XslTransform::Transform(const String\&, const String\&) मेथड


इनपुट फ़ाइल में XML डेटा को परिवर्तित करता है और परिणाम को आउटपुट फ़ाइल में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | परिवर्तित करने के लिए स्रोत दस्तावेज़ का URL। |
| outputfile | const [String](../../../system/string/)\& | आउटपुट फ़ाइल का URL। |

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* कक्षा [XmlReader](../../../system.xml/xmlreader/)
* कक्षा [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* कक्षा [XsltArgumentList](../../xsltargumentlist/)
* कक्षा [XmlResolver](../../../system.xml/xmlresolver/)
* कक्षा [XslTransform](../)
* कक्षा [XmlWriter](../../../system.xml/xmlwriter/)
* कक्षा [Stream](../../../system.io/stream/)
* कक्षा [TextWriter](../../../system.io/textwriter/)
* कक्षा [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* कक्षा [String](../../../system/string/)
* नेमस्पेस [System::Xml::Xsl](../../)
* लाइब्रेरी [Aspose.Slides](../../../)