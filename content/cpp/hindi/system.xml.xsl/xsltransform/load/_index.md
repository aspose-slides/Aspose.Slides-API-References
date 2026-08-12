---
title: Load()
second_title: Aspose.Slides for C++ API संदर्भ
description: XmlReader में सम्मिलित XSLT शैली शीट को लोड करता है।
type: docs
weight: 27
url: /hi/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) विधि

[XmlReader](../../../system.xml/xmlreader/) में स्थित XSLT शैली शीट को लोड करता है।

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | एक [XmlReader](../../../system.xml/xmlreader/) वस्तु जो XSLT शैली शीट को सम्मिलित करती है। |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) विधि

[XmlReader](../../../system.xml/xmlreader/) में स्थित XSLT शैली शीट को लोड करता है।

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | एक [XmlReader](../../../system.xml/xmlreader/) वस्तु जो XSLT शैली शीट को सम्मिलित करती है। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | कोई भी शैली पत्रक जो **xsl:import** और **xsl:include** तत्वों में संदर्भित हैं, उन्हें लोड करने के लिए उपयोग किया गया [XmlResolver](../../../system.xml/xmlresolver/)। यदि यह **nullptr** है, तो बाहरी संसाधनों को हल नहीं किया जाता है। यह [XmlResolver](../../../system.xml/xmlresolver/) इस विधि के पूरा होने के बाद कैश नहीं किया जाता है। |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) विधि

IXPathNavigable में स्थित XSLT शैली शीट को लोड करता है।

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable इंटरफ़ेस को लागू करने वाली एक वस्तु। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या XSLT शैली शीट को सम्मिलित करने वाला एक XPathDocument। |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) विधि

IXPathNavigable में स्थित XSLT शैली शीट को लोड करता है।

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable इंटरफ़ेस को लागू करने वाली एक वस्तु। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या XSLT शैली शीट को सम्मिलित करने वाला एक XPathDocument। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | कोई भी शैली पत्रक जो **xsl:import** और **xsl:include** तत्वों में संदर्भित हैं, उन्हें लोड करने के लिए उपयोग किया गया [XmlResolver](../../../system.xml/xmlresolver/)। यदि यह **nullptr** है, तो बाहरी संसाधनों को हल नहीं किया जाता है। यह [XmlResolver](../../../system.xml/xmlresolver/) इस विधि के पूरा होने के बाद कैश नहीं किया जाता है। |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) विधि

XPathNavigator में स्थित XSLT शैली शीट को लोड करता है।

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | एक XPathNavigator वस्तु जो XSLT शैली शीट को सम्मिलित करती है। |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) विधि

XPathNavigator में स्थित XSLT शैली शीट को लोड करता है।

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | एक XPathNavigator वस्तु जो XSLT शैली शीट को सम्मिलित करती है। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | कोई भी शैली पत्रक जो **xsl:import** और **xsl:include** तत्वों में संदर्भित हैं, उन्हें लोड करने के लिए उपयोग किया गया [XmlResolver](../../../system.xml/xmlresolver/)। यदि यह **nullptr** है, तो बाहरी संसाधनों को हल नहीं किया जाता है। यह [XmlResolver](../../../system.xml/xmlresolver/) इस विधि के पूरा होने के बाद कैश नहीं किया जाता है। |

## XslTransform::Load(const String\&) विधि

एक URL द्वारा निर्दिष्ट XSLT शैली शीट को लोड करता है।

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL जो लोड करने के लिए XSLT शैली शीट को निर्दिष्ट करता है। |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) विधि

एक URL द्वारा निर्दिष्ट XSLT शैली शीट को लोड करता है।

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL जो लोड करने के लिए XSLT शैली शीट को निर्दिष्ट करता है। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) जिसका उपयोग शैली शीट और **xsl:import** तथा **xsl:include** तत्वों में संदर्भित किसी भी शैली शीट(s) को लोड करने के लिए किया जाता है। यदि यह **nullptr** है, तो कोई उपयोगकर्ता क्रेडेंशियल नहीं वाले डिफ़ॉल्ट [XmlUrlResolver](../../../system.xml/xmlurlresolver/) का उपयोग शैली शीट खोलने के लिए किया जाता है। डिफ़ॉल्ट [XmlUrlResolver](../../../system.xml/xmlurlresolver/) शैली शीट में किसी भी बाहरी संसाधन को हल करने के लिए उपयोग नहीं किया जाता, इसलिए **xsl:import** और **xsl:include** तत्व हल नहीं होते। इस [XmlResolver](../../../system.xml/xmlresolver/) को इस विधि के पूरा होने के बाद कैश नहीं किया जाता। |

## देखें

* टाइपडैफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlReader](../../../system.xml/xmlreader/)
* क्लास [XslTransform](../)
* क्लास [XmlResolver](../../../system.xml/xmlresolver/)
* क्लास [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* क्लास [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml::Xsl](../../)
* लाइब्रेरी [Aspose.Slides](../../../)