---
title: PrependChildElement()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में नेमस्पेस प्रीफ़िक्स, लोकल नाम, और नेमस्पेस URI का उपयोग करके निर्दिष्ट मान के साथ एक नया चाइल्ड एलिमेंट बनाता है।
type: docs
weight: 989
url: /hi/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) विधि


वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में नेमस्पेस प्रीफ़िक्स, लोकल नाम और नेमस्पेस URI के साथ निर्दिष्ट मान का उपयोग करके एक नया चाइल्ड एलिमेंट बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | नए चाइल्ड एलिमेंट का नेमस्पेस प्रीफ़िक्स (यदि हो)। |
| localName | [String](../../../system/string/) | नए चाइल्ड एलिमेंट का लोकल नाम (यदि हो)। |
| namespaceURI | [String](../../../system/string/) | नए चाइल्ड एलिमेंट का नेमस्पेस URI (यदि हो)। [String::Empty](../../../system/string/empty/) और **nullptr** समान हैं। |
| value | [String](../../../system/string/) | नए चाइल्ड एलिमेंट का मान। यदि [String::Empty](../../../system/string/empty/) या **nullptr** पास किया जाता है, तो एक खाली एलिमेंट बनाया जाता है। |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XPathNavigator](../)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)