---
title: CreateAttribute()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: वर्तमान element नोड पर निर्दिष्ट मान के साथ namespace prefix, local name और namespace URI का उपयोग करके एक attribute node बनाता है।
type: docs
weight: 1041
url: /hi/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) मेथड

वर्तमान element नोड पर निर्दिष्ट मान के साथ namespace prefix, local name और namespace URI का उपयोग करके एक attribute node बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | नए attribute node का namespace prefix (यदि कोई हो)। |
| localName | [String](../../../system/string/) | नए attribute node का local name जो [String::Empty](../../../system/string/empty/) या **nullptr** नहीं हो सकता। |
| namespaceURI | [String](../../../system/string/) | नए attribute node के लिए namespace URI (यदि कोई हो)। |
| value | [String](../../../system/string/) | नए attribute node का मान। यदि [String::Empty](../../../system/string/empty/) या **nullptr** पास किया जाता है, तो एक खाली attribute node बनाया जाता है। |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XPathNavigator](../)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)