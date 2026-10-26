---
title: Load()
second_title: Aspose.Slides for C++ API संदर्भ
description: XmlReader में सम्मिलित स्टाइल शीट को कंपाइल करता है।
type: docs
weight: 27
url: /hi/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) विधि

[XmlReader](../../../system.xml/xmlreader/) में सम्मिलित स्टाइल शीट को कंपाइल करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | स्टाइल शीट को सम्मिलित करने वाला एक [XmlReader](../../../system.xml/xmlreader/)। |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) विधि

[XmlReader](../../../system.xml/xmlreader/) में सम्मिलित XSLT स्टाइल शीट को कंपाइल करता है। [XmlResolver](../../../system.xml/xmlresolver/) किसी भी XSLT **import** या **include** तत्वों को हल करता है और XSLT सेटिंग्स स्टाइल शीट की अनुमतियों को निर्धारित करती हैं।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | स्टाइल शीट को सम्मिलित करने वाला [XmlReader](../../../system.xml/xmlreader/)। |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | स्टाइल शीट पर लागू करने के लिये [XsltSettings](../../xsltsettings/)। यदि यह **nullptr** है तो [XsltSettings::get_Default](../../xsltsettings/get_default/) सेटिंग लागू होती है। |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **import** और **include** तत्वों में संदर्भित किसी भी स्टाइल शीट को हल करने के लिये उपयोग किया जाने वाला [XmlResolver](../../../system.xml/xmlresolver/)। यदि यह **nullptr** है तो बाहरी संसाधनों को हल नहीं किया जाता। |

## XslCompiledTransform::Load(const String\&) विधि

निर्दिष्ट URI पर स्थित स्टाइल शीट को लोड और कंपाइल करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | स्टाइल शीट का URI। |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) विधि

URI द्वारा निर्दिष्ट XSLT स्टाइल शीट को लोड और कंपाइल करता है। [XmlResolver](../../../system.xml/xmlresolver/) किसी भी XSLT **import** या **include** तत्वों को हल करता है और XSLT सेटिंग्स स्टाइल शीट की अनुमतियों को निर्धारित करती हैं।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | स्टाइल शीट का URI। |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | स्टाइल शीट पर लागू करने के लिये [XsltSettings](../../xsltsettings/)। यदि यह **nullptr** है तो [XsltSettings::get_Default](../../xsltsettings/get_default/) सेटिंग लागू होती है। |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | स्टाइल शीट URI और XSLT **import** तथा **include** तत्वों में उल्लेखित किसी भी स्टाइल शीट को हल करने के लिये उपयोग किया जाने वाला [XmlResolver](../../../system.xml/xmlresolver/)। |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) विधि

IXPathNavigable ऑब्जेक्ट में सम्मिलित स्टाइल शीट को कंपाइल करता है।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable इंटरफ़ेस को लागू करने वाला ऑब्जेक्ट। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या एक XPathDocument जो स्टाइल शीट को सम्मिलित करता है। |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) विधि

IXPathNavigable में सम्मिलित XSLT स्टाइल शीट को कंपाइल करता है। [XmlResolver](../../../system.xml/xmlresolver/) किसी भी XSLT **import** या **include** तत्वों को हल करता है और XSLT सेटिंग्स स्टाइल शीट की अनुमतियों को निर्धारित करती हैं।

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable इंटरफ़ेस को लागू करने वाला ऑब्जेक्ट। यह या तो एक [XmlNode](../../../system.xml/xmlnode/) (आमतौर पर एक [XmlDocument](../../../system.xml/xmldocument/)) हो सकता है, या एक XPathDocument जो स्टाइल शीट को सम्मिलित करता है। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | स्टाइल शीट पर लागू करने के लिये [XsltSettings](../../xsltsettings/)। यदि यह **nullptr** है तो [XsltSettings::get_Default](../../xsltsettings/get_default/) सेटिंग लागू होती है। |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | XSLT **import** और **include** तत्वों में उल्लेखित किसी भी स्टाइल शीट को हल करने के लिये उपयोग किया जाने वाला [XmlResolver](../../../system.xml/xmlresolver/)। यदि यह **nullptr** है तो बाहरी संसाधनों को हल नहीं किया जाता। |

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlReader](../../../system.xml/xmlreader/)
* क्लास [XslCompiledTransform](../)
* क्लास [XsltSettings](../../xsltsettings/)
* क्लास [XmlResolver](../../../system.xml/xmlresolver/)
* क्लास [String](../../../system/string/)
* क्लास [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* नामस्थान [System::Xml::Xsl](../../)
* लाइब्रेरी [Aspose.Slides](../../../)