---
title: MoveToChild()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: XPathNavigator को निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले चाइल्ड नोड पर ले जाता है।
type: docs
weight: 690
url: /hi/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) मेथड

[XPathNavigator](../) को निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले चाइल्ड नोड पर ले जाता है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | जिस चाइल्ड नोड पर ले जाना है उसका स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | जिस चाइल्ड नोड पर ले जाना है उसका नेमस्पेस URI। |

### रिटर्न वैल्यू

**true** यदि [XPathNavigator](../) चाइल्ड नोड पर सफलतापूर्वक ले जाता है; अन्यथा **false**। यदि **false**, तो [XPathNavigator](../) की स्थिति अपरिवर्तित रहती है।

## XPathNavigator::MoveToChild(XPathNodeType) मेथड

[XPathNavigator](../) को निर्दिष्ट XPathNodeType के चाइल्ड नोड पर ले जाता है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | जिस चाइल्ड नोड पर ले जाना है उसका XPathNodeType। |

### रिटर्न वैल्यू

**true** यदि [XPathNavigator](../) चाइल्ड नोड पर सफलतापूर्वक ले जाता है; अन्यथा **false**। यदि **false**, तो [XPathNavigator](../) की स्थिति अपरिवर्तित रहती है।

## संबंधित देखें

* एनम [XPathNodeType](../../xpathnodetype/)
* क्लास [String](../../../system/string/)
* क्लास [XPathNavigator](../)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)