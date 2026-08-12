---
title: Matches()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि वर्तमान नोड निर्दिष्ट XPathExpression से मेल खाता है या नहीं।
type: docs
weight: 820
url: /hi/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) विधि


निर्धारित करता है कि वर्तमान नोड निर्दिष्ट [XPathExpression](../../xpathexpression/) से मेल खाता है या नहीं।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | एक [XPathExpression](../../xpathexpression/) ऑब्जेक्ट जिसमें संकलित [XPath](../../) अभिव्यक्ति है। |

### रिटर्न मान

**true** यदि वर्तमान नोड [XPathExpression](../../xpathexpression/) से मेल खाता है; अन्यथा **false**।

## XPathNavigator::Matches(String) विधि


निर्धारित करता है कि वर्तमान नोड निर्दिष्ट [XPath](../../) अभिव्यक्ति से मेल खाता है या नहीं।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [XPath](../../) अभिव्यक्ति। |

### रिटर्न मान

**true** यदि वर्तमान नोड निर्दिष्ट [XPath](../../) अभिव्यक्ति से मेल खाता है; अन्यथा **false**।

## संबंधित

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XPathExpression](../../xpathexpression/)
* क्लास [XPathNavigator](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)