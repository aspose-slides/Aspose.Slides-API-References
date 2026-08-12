---
title: InsertAfter()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान चयनित नोड के बाद एक नया सहोदर नोड बनाने के लिए उपयोग किया जाने वाला XmlWriter ऑब्जेक्ट लौटाता है।
type: docs
weight: 898
url: /hi/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() विधि

वर्तमान चयनित नोड के बाद एक नया सहोदर नोड बनाने के लिए उपयोग किया जाने वाला [XmlWriter](../../../system.xml/xmlwriter/) ऑब्जेक्ट लौटाता है।

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### रिटर्न वैल्यू

वर्तमान चयनित नोड के बाद एक नया सहोदर नोड बनाने के लिए उपयोग किया जाने वाला [XmlWriter](../../../system.xml/xmlwriter/) ऑब्जेक्ट।

## XPathNavigator::InsertAfter(String) विधि

निर्दिष्ट XML स्ट्रिंग का उपयोग कर वर्तमान चयनित नोड के बाद एक नया सहोदर नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | नए सहोदर नोड के लिए XML डेटा स्ट्रिंग। |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) विधि

निर्दिष्ट [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट की XML सामग्री का उपयोग कर वर्तमान चयनित नोड के बाद एक नया सहोदर नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | नए सहोदर नोड के लिए XML डेटा पर स्थित एक [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट। |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) विधि

निर्दिष्ट [XPathNavigator](../) ऑब्जेक्ट में नोड्स का उपयोग कर वर्तमान चयनित नोड के बाद एक नया सहोदर नोड बनाता है।

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | नए सहोदर नोड के रूप में जोड़ने के लिए नोड पर स्थित एक [XPathNavigator](../) ऑब्जेक्ट। |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlWriter](../../../system.xml/xmlwriter/)
* क्लास [XPathNavigator](../)
* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../../../system.xml/xmlreader/)
* नेमस्पेस [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)