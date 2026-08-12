---
title: InsertBefore()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: वर्तमान में चयनित नोड से पहले नया भाई नोड बनाने के लिए उपयोग किया जाने वाला XmlWriter ऑब्जेक्ट लौटाता है।
type: docs
weight: 911
url: /hi/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() मेथड


वर्तमान में चयनित नोड से पहले एक नया भाई नोड बनाने के लिए उपयोग किया जाने वाला [XmlWriter](../../../system.xml/xmlwriter/) ऑब्जेक्ट लौटाता है।

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```


### रिटर्न वैल्यू

वर्तमान में चयनित नोड से पहले एक नया भाई नोड बनाने के लिए उपयोग किया जाने वाला [XmlWriter](../../../system.xml/xmlwriter/) ऑब्जेक्ट।

## XPathNavigator::InsertBefore(String) मेथड


निर्दिष्ट XML स्ट्रिंग का उपयोग करके वर्तमान में चयनित नोड से पहले एक नया भाई नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | नया भाई नोड के लिए XML डेटा स्ट्रिंग। |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) मेथड


निर्दिष्ट [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट की XML सामग्री का उपयोग करके वर्तमान में चयनित नोड से पहले एक नया भाई नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | नया भाई नोड के लिए XML डेटा पर स्थित एक [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट। |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) मेथड


निर्दिष्ट [XPathNavigator](../) में मौजूद नोड्स का उपयोग करके वर्तमान में चयनित नोड से पहले एक नया भाई नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | नया भाई नोड के रूप में जोड़ने के लिए नोड पर स्थित एक [XPathNavigator](../) ऑब्जेक्ट। |

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlWriter](../../../system.xml/xmlwriter/)
* क्लास [XPathNavigator](../)
* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../../../system.xml/xmlreader/)
* नामस्थान [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)