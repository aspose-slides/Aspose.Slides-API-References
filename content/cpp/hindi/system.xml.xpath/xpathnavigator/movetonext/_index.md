---
title: MoveToNext()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो XPathNavigator को वर्तमान नोड के अगले सहोदर नोड पर ले जाता है।
type: docs
weight: 586
url: /hi/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() विधि

जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो [XPathNavigator](../) को वर्तमान नोड के अगले सहोदर नोड पर ले जाता है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### रिटर्न वैल्यू

**true** यदि [XPathNavigator](../) सफलतापूर्वक अगले सहोदर नोड पर ले जाता है; अन्यथा **false** यदि और कोई सहोदर नोड नहीं है या यदि [XPathNavigator](../) वर्तमान में किसी विशेषता नोड पर स्थित है। यदि **false**, तो [XPathNavigator](../) की स्थिति अपरिवर्तित रहती है।

## XPathNavigator::MoveToNext(String, String) विधि

[XPathNavigator](../) को निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले अगले सहोदर नोड पर ले जाता है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ले जाने वाले अगले सहोदर नोड का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | ले जाने वाले अगले सहोदर नोड का नेमस्पेस URI। |

### रिटर्न वैल्यू

**true** यदि [XPathNavigator](../) सफलतापूर्वक अगले सहोदर नोड पर ले जाता है; **false** यदि और कोई सहोदर नोड नहीं है, या यदि [XPathNavigator](../) वर्तमान में किसी विशेषता नोड पर स्थित है। यदि **false**, तो [XPathNavigator](../) की स्थिति अपरिवर्तित रहती है।

## XPathNavigator::MoveToNext(XPathNodeType) विधि

[XPathNavigator](../) को वर्तमान नोड के अगले सहोदर नोड पर ले जाता है जो निर्दिष्ट XPathNodeType से मेल खाता है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | ले जाने वाले सहोदर नोड का XPathNodeType। |

### रिटर्न वैल्यू

**true** यदि [XPathNavigator](../) सफलतापूर्वक अगले सहोदर नोड पर ले जाता है; अन्यथा **false** यदि और कोई सहोदर नोड नहीं है या यदि [XPathNavigator](../) वर्तमान में किसी विशेषता नोड पर स्थित है। यदि **false**, तो [XPathNavigator](../) की स्थिति अपरिवर्तित रहती है।

## देखें अन्य

* Enum [XPathNodeType](../../xpathnodetype/)
* क्लास [XPathNavigator](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)