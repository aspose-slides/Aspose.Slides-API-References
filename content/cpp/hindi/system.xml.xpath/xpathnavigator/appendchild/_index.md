---
title: AppendChild()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान नोड के चाइल्ड नोड्स की सूची के अंत में एक या अधिक नए चाइल्ड नोड्स बनाने के लिए उपयोग किया जाने वाला XmlWriter ऑब्जेक्ट लौटाता है।
type: docs
weight: 885
url: /hi/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() मेथड

वर्तमान नोड के चाइल्ड नोड्स की सूची के अंत में एक या अधिक नए चाइल्ड नोड्स बनाने के लिए उपयोग किए जाने वाले [XmlWriter](../../../system.xml/xmlwriter/) ऑब्जेक्ट को लौटाता है।

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### रिटर्न वैल्यू

वर्तमान नोड के चाइल्ड नोड्स की सूची के अंत में नए चाइल्ड नोड्स बनाने के लिए उपयोग किए जाने वाला [XmlWriter](../../../system.xml/xmlwriter/) ऑब्जेक्ट।

## XPathNavigator::AppendChild(String) मेथड

निर्दिष्ट XML डेटा स्ट्रिंग का उपयोग करके वर्तमान नोड के चाइल्ड नोड्स की सूची के अंत में एक नया चाइल्ड नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | नए चाइल्ड नोड के लिए XML डेटा स्ट्रिंग। |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) मेथड

निर्दिष्ट [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट की XML सामग्री का उपयोग करके वर्तमान नोड के चाइल्ड नोड्स की सूची के अंत में एक नया चाइल्ड नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | नए चाइल्ड नोड के लिए XML डेटा पर स्थित [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट। |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) मेथड

निर्दिष्ट [XPathNavigator](../) में नोड्स का उपयोग करके वर्तमान नोड के चाइल्ड नोड्स की सूची के अंत में एक नया चाइल्ड नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | नए चाइल्ड नोड के रूप में जोड़ने के लिए नोड पर स्थित [XPathNavigator](../) ऑब्जेक्ट। |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlWriter](../../../system.xml/xmlwriter/)
* क्लास [XPathNavigator](../)
* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../../../system.xml/xmlreader/)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)