---
title: PrependChild()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में नया चाइल्ड नोड बनाने के लिए उपयोग किए जाने वाले XmlWriter ऑब्जेक्ट को लौटाता है।
type: docs
weight: 872
url: /hi/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() मेथड

[XmlWriter](../../../system.xml/xmlwriter/) ऑब्जेक्ट लौटाता है जो वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में नया चाइल्ड नोड बनाने के लिए उपयोग किया जाता है।

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### रिटर्न वैल्यू

[XmlWriter](../../../system.xml/xmlwriter/) ऑब्जेक्ट का उपयोग वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में नया चाइल्ड नोड बनाने के लिए किया जाता है।

## XPathNavigator::PrependChild(String) मेथड

निर्दिष्ट XML स्ट्रिंग का उपयोग करके वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में एक नया चाइल्ड नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | नए चाइल्ड नोड के लिए XML डेटा स्ट्रिंग। |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) मेथड

निर्दिष्ट [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट की XML सामग्री का उपयोग करके वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में एक नया चाइल्ड नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | नए चाइल्ड नोड के लिए XML डेटा पर स्थित [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट। |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) मेथड

निर्दिष्ट [XPathNavigator](../) ऑब्जेक्ट के नोड्स का उपयोग करके वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में एक नया चाइल्ड नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | नए चाइल्ड नोड के रूप में जोड़ने के लिए नोड पर स्थित [XPathNavigator](../) ऑब्जेक्ट। |

## देखें भी

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlWriter](../../../system.xml/xmlwriter/)
* क्लास [XPathNavigator](../)
* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../../../system.xml/xmlreader/)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)