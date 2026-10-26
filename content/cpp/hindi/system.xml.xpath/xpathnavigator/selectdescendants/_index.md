---
title: SelectDescendants()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: वर्तमान नोड के सभी उत्तराधिकारी नोड्स को चुनता है जिनका XPathNodeType मेल खाता है।
type: docs
weight: 859
url: /hi/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) मेथड

वर्तमान नोड के सभी उत्तराधिकारी नोड्स को चुनता है जिनका XPathNodeType मेल खाता है।

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | विरासत में मिले नोड्स का XPathNodeType। |
| matchSelf | **bool** | **true** को चयन में संदर्भ नोड शामिल करने के लिए; अन्यथा, **false**। |

### वापसी मान

एक [XPathNodeIterator](../../xpathnodeiterator/) जिसमें चयनित नोड्स होते हैं।

## XPathNavigator::SelectDescendants(String, String, bool) मेथड

वर्तमान नोड के सभी उत्तराधिकारी नोड्स को चुनता है जिनका स्थानीय नाम और निर्दिष्ट नेमस्पेस URI है।

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | विरासत में मिले नोड्स का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | विरासत में मिले नोड्स का नेमस्पेस URI। |
| matchSelf | **bool** | **true** को चयन में संदर्भ नोड शामिल करने के लिए; अन्यथा, **false**। |

### वापसी मान

एक [XPathNodeIterator](../../xpathnodeiterator/) जिसमें चयनित नोड्स होते हैं।

## संबंधित देखें

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)