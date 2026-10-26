---
title: AddNamespace()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: दिए गए नेमस्पेस को संग्रह में जोड़ता है।
type: docs
weight: 66
url: /hi/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) विधि

दिए गए नेमस्पेस को संग्रह में जोड़ता है।

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | जो प्रीफ़िक्स जोड़ रहे नेमस्पेस के साथ संबद्ध किया जाता है। डिफ़ॉल्ट नेमस्पेस जोड़ने के लिए [String::Empty](../../../system/string/empty/) का उपयोग करें। यदि [XmlNamespaceManager](../) का उपयोग XML Path Language ([XPath](../../../system.xml.xpath/)) अभिव्यक्ति में नेमस्पेस को हल करने के लिए किया जाएगा, तो एक प्रीफ़िक्स निर्दिष्ट करना आवश्यक है। यदि [XPath](../../../system.xml.xpath/) अभिव्यक्ति में प्रीफ़िक्स नहीं होता है, तो माना जाता है कि नेमस्पेस यूनिफ़ॉर्म रिसोर्स आइडेंटिफ़ायर (URI) खाली नेमस्पेस है। [XPath](../../../system.xml.xpath/) अभिव्यक्तियों और [XmlNamespaceManager](../) के बारे में अधिक जानकारी के लिए, XmlNode::SelectNodes(String) और XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) विधियों को देखें। |
| uri | [String](../../../system/string/) | जोड़ने के लिए नेमस्पेस। |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNamespaceManager](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)