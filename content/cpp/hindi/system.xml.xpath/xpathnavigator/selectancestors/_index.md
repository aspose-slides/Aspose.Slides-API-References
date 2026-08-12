---
title: SelectAncestors()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान नोड के सभी पूर्वज नोड्स को चुनता है जिनका XPathNodeType मेल खाता है।
type: docs
weight: 846
url: /hi/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) मेथड

वर्तमान नोड के सभी पूर्वज नोड्स को चुनता है जिनका XPathNodeType मेल खाता है।

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | पूर्वज नोड्स का XPathNodeType। |
| matchSelf | **bool** | चयन में संदर्भ नोड को शामिल करने के लिए, **true**; अन्यथा, **false**। |

### रिटर्न वैल्यू

एक [XPathNodeIterator](../../xpathnodeiterator/) जिसमें चयनित नोड्स होते हैं। लौटाए गए नोड्स दस्तावेज़ क्रम के उल्टे क्रम में होते हैं।

## XPathNavigator::SelectAncestors(String, String, bool) मेथड

वर्तमान नोड के सभी पूर्वज नोड्स को चुनता है जिनका स्थानीय नाम और namespace URI निर्दिष्ट है।

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | पूर्वज नोड्स का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | पूर्वज नोड्स का namespace URI। |
| matchSelf | **bool** | चयन में संदर्भ नोड को शामिल करने के लिए, **true**; अन्यथा, **false**। |

### रिटर्न वैल्यू

एक [XPathNodeIterator](../../xpathnodeiterator/) जिसमें चयनित नोड्स होते हैं। लौटाए गए नोड्स दस्तावेज़ क्रम के उल्टे क्रम में होते हैं।

## संबंधित देखें

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)