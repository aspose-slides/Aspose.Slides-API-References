---
title: Transform()
second_title: Aspose.Slides for C++ एपीआई रेफ़रेंस
description: IXPathNavigable ऑब्जेक्ट द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफ़ॉर्म को निष्पादित करता है और परिणामों को एक XmlWriter में आउटपुट करता है।
type: docs
weight: 40
url: /hi/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) विधि

IXPathNavigable ऑब्जेक्ट द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable इंटरफ़ेस को लागू करने वाला एक ऑब्जेक्ट। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित किए जाने वाले डेटा होते हैं। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिसमें आप आउटपुट देना चाहते हैं। यदि शैलीपत्र में **xsl:output** तत्व मौजूद है, तो आपको [XmlWriter](../../../system.xml/xmlwriter/) को [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ऑब्जेक्ट का उपयोग करके बनाना चाहिए जो [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) मान से वापस प्राप्त होता है। यह सुनिश्चित करता है कि [XmlWriter](../../../system.xml/xmlwriter/) के पास सही आउटपुट सेटिंग्स हों। |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) विधि

IXPathNavigable ऑब्जेक्ट द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है। [XsltArgumentList](../../xsltargumentlist/) अतिरिक्त रन-टाइम आर्ग्युमेंट्स प्रदान करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable इंटरफ़ेस को लागू करने वाला एक ऑब्जेक्ट। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित किए जाने वाले डेटा होते हैं। |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो ट्रांसफ़ॉर्म के इनपुट के रूप में उपयोग होते हैं। यह मान **nullptr** हो सकता है। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिसमें आप आउटपुट देना चाहते हैं। यदि शैलीपत्र में **xsl:output** तत्व मौजूद है, तो आपको [XmlWriter](../../../system.xml/xmlwriter/) को [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ऑब्जेक्ट का उपयोग करके बनाना चाहिए जो [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) मान से वापस प्राप्त होता है। यह सुनिश्चित करता है कि [XmlWriter](../../../system.xml/xmlwriter/) के पास सही आउटपुट सेटिंग्स हों। |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) विधि

IXPathNavigable ऑब्जेक्ट द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक TextWriter में आउटपुट करता है। [XsltArgumentList](../../xsltargumentlist/) अतिरिक्त रन-टाइम आर्ग्युमेंट्स प्रदान करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable इंटरफ़ेस को लागू करने वाला एक ऑब्जेक्ट। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित किए जाने वाले डेटा होते हैं। |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो ट्रांसफ़ॉर्म के इनपुट के रूप में उपयोग होते हैं। यह मान **nullptr** हो सकता है। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter जिसमें आप आउटपुट देना चाहते हैं। |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) विधि

IXPathNavigable ऑब्जेक्ट द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक स्ट्रीम में आउटपुट करता है। [XsltArgumentList](../../xsltargumentlist/) अतिरिक्त रन-टाइम आर्ग्युमेंट्स प्रदान करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable इंटरफ़ेस को लागू करने वाला एक ऑब्जेक्ट। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या वह XPathDocument जिसमें परिवर्तित किए जाने वाले डेटा होते हैं। |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो ट्रांसफ़ॉर्म के इनपुट के रूप में उपयोग होते हैं। यह मान **nullptr** हो सकता है। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिसमें आप आउटपुट देना चाहते हैं। |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) विधि

[XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | इनपुट दस्तावेज़ वाली [XmlReader](../../../system.xml/xmlreader/)। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिसमें आप आउटपुट देना चाहते हैं। यदि शैलीपत्र में **xsl:output** तत्व मौजूद है, तो आपको [XmlWriter](../../../system.xml/xmlwriter/) को [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ऑब्जेक्ट का उपयोग करके बनाना चाहिए जो [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) मान से वापस प्राप्त होता है। यह सुनिश्चित करता है कि [XmlWriter](../../../system.xml/xmlwriter/) के पास सही आउटपुट सेटिंग्स हों। |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) विधि

[XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है। [XsltArgumentList](../../xsltargumentlist/) अतिरिक्त रन-टाइम आर्ग्युमेंट्स प्रदान करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | इनपुट दस्तावेज़ वाली एक [XmlReader](../../../system.xml/xmlreader/)। |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो ट्रांसफ़ॉर्म के इनपुट के रूप में उपयोग होते हैं। यह मान **nullptr** हो सकता है। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिसमें आप आउटपुट देना चाहते हैं। यदि शैलीपत्र में **xsl:output** तत्व मौजूद है, तो आपको [XmlWriter](../../../system.xml/xmlwriter/) को [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ऑब्जेक्ट का उपयोग करके बनाना चाहिए जो [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) मान से वापस प्राप्त होता है। यह सुनिश्चित करता है कि [XmlWriter](../../../system.xml/xmlwriter/) के पास सही आउटपुट सेटिंग्स हों। |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) विधि

[XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक TextWriter में आउटपुट करता है। [XsltArgumentList](../../xsltargumentlist/) अतिरिक्त रन-टाइम आर्ग्युमेंट्स प्रदान करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | इनपुट दस्तावेज़ वाली एक [XmlReader](../../../system.xml/xmlreader/)। |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो ट्रांसफ़ॉर्म के इनपुट के रूप में उपयोग होते हैं। यह मान **nullptr** हो सकता है। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter जिसमें आप आउटपुट देना चाहते हैं। |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) विधि

[XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक स्ट्रीम में आउटपुट करता है। [XsltArgumentList](../../xsltargumentlist/) अतिरिक्त रन-टाइम आर्ग्युमेंट्स प्रदान करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | इनपुट दस्तावेज़ वाली एक [XmlReader](../../../system.xml/xmlreader/)। |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो ट्रांसफ़ॉर्म के इनपुट के रूप में उपयोग होते हैं। यह मान **nullptr** हो सकता है। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिसमें आप आउटपुट देना चाहते हैं। |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) विधि

URI द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | इनपुट दस्तावेज़ का URI। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिसमें आप आउटपुट देना चाहते हैं। यदि शैलीपत्र में **xsl:output** तत्व मौजूद है, तो आपको [XmlWriter](../../../system.xml/xmlwriter/) को [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ऑब्जेक्ट का उपयोग करके बनाना चाहिए जो [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) मान से वापस प्राप्त होता है। यह सुनिश्चित करता है कि [XmlWriter](../../../system.xml/xmlwriter/) के पास सही आउटपुट सेटिंग्स हों। |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) विधि

URI द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है। [XsltArgumentList](../../xsltargumentlist/) अतिरिक्त रन-टाइम आर्ग्युमेंट्स प्रदान करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | इनपुट दस्तावेज़ का URI। |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो ट्रांसफ़ॉर्म के इनपुट के रूप में उपयोग होते हैं। यह मान **nullptr** हो सकता है। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिसमें आप आउटपुट देना चाहते हैं। यदि शैलीपत्र में **xsl:output** तत्व मौजूद है, तो आपको [XmlWriter](../../../system.xml/xmlwriter/) को [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ऑब्जेक्ट का उपयोग करके बनाना चाहिए जो [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) मान से वापस प्राप्त होता है। यह सुनिश्चित करता है कि [XmlWriter](../../../system.xml/xmlwriter/) के पास सही आउटपुट सेटिंग्स हों। |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) विधि

URI द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक TextWriter में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | इनपुट दस्तावेज़ का URI। |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो ट्रांसफ़ॉर्म के इनपुट के रूप में उपयोग होते हैं। यह मान **nullptr** हो सकता है। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter जिसमें आप आउटपुट देना चाहते हैं। |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) विधि

URI द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक स्ट्रीम में आउटपुट करता है। [XsltArgumentList](../../xsltargumentlist/) अतिरिक्त रन-टाइम आर्ग्युमेंट्स प्रदान करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | इनपुट दस्तावेज़ का URI। |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो ट्रांसफ़ॉर्म के इनपुट के रूप में उपयोग होते हैं। यह मान **nullptr** हो सकता है। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिसमें आप आउटपुट देना चाहते हैं। |

## XslCompiledTransform::Transform(const String\&, const String\&) विधि

URI द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक फ़ाइल में आउटपुट करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | इनपुट दस्तावेज़ का URI। |
| resultsFile | const [String](../../../system/string/)\& | आउटपुट फ़ाइल का URI। |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) विधि

[XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है। [XsltArgumentList](../../xsltargumentlist/) अतिरिक्त रन-टाइम आर्ग्युमेंट्स प्रदान करता है और [XmlResolver](../../../system.xml/xmlresolver/) XSLT **document()** फ़ंक्शन को हल करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | इनपुट दस्तावेज़ वाली एक [XmlReader](../../../system.xml/xmlreader/)। |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | एक [XsltArgumentList](../../xsltargumentlist/) जिसमें नेमस्पेस-योग्य आर्ग्युमेंट्स होते हैं जो ट्रांसफ़ॉर्म के इनपुट के रूप में उपयोग होते हैं। यह मान **nullptr** हो सकता है। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिसमें आप आउटपुट देना चाहते हैं। यदि शैलीपत्र में **xsl:output** तत्व मौजूद है, तो आपको [XmlWriter](../../../system.xml/xmlwriter/) को [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ऑब्जेक्ट का उपयोग करके बनाना चाहिए जो [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) मान से वापस प्राप्त होता है। यह सुनिश्चित करता है कि [XmlWriter](../../../system.xml/xmlwriter/) के पास सही आउटपुट सेटिंग्स हों। |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** फ़ंक्शन को हल करने के लिए उपयोग किया गया [XmlResolver](../../../system.xml/xmlresolver/)। यदि यह **nullptr** है, तो **document()** फ़ंक्शन हल नहीं किया जाएगा। |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) विधि

IXPathNavigable ऑब्जेक्ट द्वारा निर्दिष्ट इनपुट दस्तावेज़ का उपयोग करके ट्रांसफॉर्म निष्पादित करता है और परिणामों को एक [XmlWriter](../../../system.xml/xmlwriter/) में आउटपुट करता है। [XsltArgumentList](../../xsltargumentlist/) अतिरिक्त रन-टाइम आर्ग्युमेंट्स प्रदान करता है और [XmlResolver](../../../system.xml/xmlresolver/) XSLT **document()** फ़ंक्शन को हल करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable ऑब्जेक्ट द्वारा निर्दिष्ट वह दस्तावेज़ जिसे ट्रांसफ़ॉर्म किया जाना है। |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) के रूप में आर्ग्युमेंट सूची। |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | वह [XmlWriter](../../../system.xml/xmlwriter/) जिसमें आप आउटपुट देना चाहते हैं। यदि शैलीपत्र में **xsl:output** तत्व मौजूद है, तो आपको [XmlWriter](../../../system.xml/xmlwriter/) को [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ऑब्जेक्ट का उपयोग करके बनाना चाहिए जो [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) मान से वापस प्राप्त होता है। यह सुनिश्चित करता है कि [XmlWriter](../../../system.xml/xmlwriter/) के पास सही आउटपुट सेटिंग्स हों। |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** फ़ंक्शन को हल करने के लिए उपयोग किया गया [XmlResolver](../../../system.xml/xmlresolver/)। यदि यह **nullptr** है, तो **document()** फ़ंक्शन हल नहीं किया जाएगा। |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)