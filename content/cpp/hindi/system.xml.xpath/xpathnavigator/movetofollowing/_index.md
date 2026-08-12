---
title: MoveToFollowing()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: XPathNavigator को दस्तावेज़ क्रम में निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले तत्व पर ले जाता है।
type: docs
weight: 703
url: /hi/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) विधि

[XPathNavigator](../) को दस्तावेज़ क्रम में निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले तत्व पर ले जाता है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | तत्व का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | तत्व का नेमस्पेस URI। |

### रिटर्न मान

**true** यदि [XPathNavigator](../) सफलतापूर्वक स्थानांतरित हुआ; अन्यथा, **false**।

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) विधि

[XPathNavigator](../) को दस्तावेज़ क्रम में निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले तत्व पर, निर्दिष्ट सीमा तक, ले जाता है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | तत्व का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | तत्व का नेमस्पेस URI। |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | उस तत्व सीमा पर स्थित [XPathNavigator](../) ऑब्जेक्ट जिससे वर्तमान [XPathNavigator](../) अगले तत्व की खोज करते समय नहीं पार करेगा। |

### रिटर्न मान

**true** यदि [XPathNavigator](../) सफलतापूर्वक स्थानांतरित हुआ; अन्यथा, **false**।

## XPathNavigator::MoveToFollowing(XPathNodeType) विधि

[XPathNavigator](../) को दस्तावेज़ क्रम में निर्दिष्ट XPathNodeType के अगले तत्व पर ले जाता है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | तत्व का XPathNodeType। XPathNodeType [XPathNodeType::Attribute](../../xpathnodetype/) या [XPathNodeType::Namespace](../../xpathnodetype/) नहीं हो सकता। |

### रिटर्न मान

**true** यदि [XPathNavigator](../) सफलतापूर्वक स्थानांतरित हुआ; अन्यथा, **false**।

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) विधि

[XPathNavigator](../) को दस्तावेज़ क्रम में निर्दिष्ट XPathNodeType के अगले तत्व पर, निर्दिष्ट सीमा तक, ले जाता है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | तत्व का XPathNodeType। XPathNodeType [XPathNodeType::Attribute](../../xpathnodetype/) या [XPathNodeType::Namespace](../../xpathnodetype/) नहीं हो सकता। |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | उस तत्व सीमा पर स्थित [XPathNavigator](../) ऑब्जेक्ट जिससे वर्तमान [XPathNavigator](../) अगले तत्व की खोज करते समय नहीं पार करेगा। |

### रिटर्न मान

**true** यदि [XPathNavigator](../) सफलतापूर्वक स्थानांतरित हुआ; अन्यथा, **false**।

## संबंधित देखें

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)