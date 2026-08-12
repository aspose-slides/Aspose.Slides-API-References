---
title: Supports()
second_title: Aspose.Slides for C++ API संदर्भ
description: जाँचता है कि DOM इम्प्लीमेंटेशन कोई विशिष्ट फ़ीचर लागू करता है या नहीं।
type: docs
weight: 482
url: /hi/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) मेथड

DOM इम्प्लीमेंटेशन किसी विशिष्ट फ़ीचर को लागू करता है या नहीं, यह परीक्षण करता है।

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| feature | [String](../../../system/string/) | परीक्षण करने वाले फ़ीचर का पैकेज नाम। यह नाम केस-सेंसिटिव नहीं है। |
| version | [String](../../../system/string/) | परीक्षण करने वाले पैकेज नाम का संस्करण संख्या। यदि संस्करण निर्दिष्ट नहीं किया गया है (null), तो फ़ीचर के किसी भी संस्करण को समर्थन देने पर मेथड **true** लौटाता है। |

### वापसी मान

**true** यदि फ़ीचर निर्दिष्ट संस्करण में लागू है; अन्यथा **false**।

## टिप्पणी

निम्न तालिका उन संयोजनों का वर्णन करती है जो **true** लौटाते हैं।

| फ़ीचर | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNode](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)