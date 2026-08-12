---
title: AppendChildElement()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान नोड के चाइल्ड नोड्स की सूची के अंत में एक नया चाइल्ड एलिमेंट नोड बनाता है, जिसमें निर्दिष्ट namespace prefix, local name और namespace URI के साथ निर्दिष्ट मान का उपयोग किया जाता है।
type: docs
weight: 1002
url: /hi/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) विधि

वर्तमान नोड के चाइल्ड नोड्स की सूची के अंत में एक नया चाइल्ड एलिमेंट नोड बनाता है, जिसमें निर्दिष्ट namespace prefix, local name और namespace URI के साथ निर्दिष्ट मान उपयोग किया जाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | नए चाइल्ड एलिमेंट नोड का namespace prefix (यदि कोई हो)। |
| localName | [String](../../../system/string/) | नए चाइल्ड एलिमेंट नोड का local name (यदि कोई हो)। |
| namespaceURI | [String](../../../system/string/) | नए चाइल्ड एलिमेंट नोड का namespace URI (यदि कोई हो)। [String::Empty](../../../system/string/empty/) और **nullptr** समान हैं। |
| value | [String](../../../system/string/) | नए चाइल्ड एलिमेंट नोड का मान। यदि [String::Empty](../../../system/string/empty/) या **nullptr** पास किए जाते हैं, तो एक खाली एलिमेंट बनाया जाता है। |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XPathNavigator](../)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)