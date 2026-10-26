---
title: SelectChildren()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान नोड के सभी चाइल्ड नोड्स को चुनता है जिनका XPathNodeType मेल खाता है।
type: docs
weight: 833
url: /hi/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) विधि

वर्तमान नोड के सभी चाइल्ड नोड्स को चुनता है जिनका XPathNodeType मेल खाता है।

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | चाइल्ड नोड्स का XPathNodeType। |

### रिटर्न वैल्यू

एक [XPathNodeIterator](../../xpathnodeiterator/) जिसमें चयनित नोड्स होते हैं।

## XPathNavigator::SelectChildren(String, String) विधि

वर्तमान नोड के सभी चाइल्ड नोड्स को चुनता है जिनका स्थानीय नाम और नेमस्पेस URI निर्दिष्ट है।

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | चाइल्ड नोड्स का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | चाइल्ड नोड्स का नेमस्पेस URI। |

### रिटर्न वैल्यू

एक [XPathNodeIterator](../../xpathnodeiterator/) जिसमें चयनित नोड्स होते हैं।

## संबंधित देखें

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XPathNodeIterator](../../xpathnodeiterator/)
* क्लास [XPathNavigator](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)