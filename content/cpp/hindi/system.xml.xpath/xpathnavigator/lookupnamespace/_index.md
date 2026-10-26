---
title: LookupNamespace()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट उपसर्ग के लिए नेमस्पेस URI लौटाता है।
type: docs
weight: 404
url: /hi/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) मेथड

निर्दिष्ट उपसर्ग के लिए नेमस्पेस URI लौटाता है।

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | वह उपसर्ग जिसका नेमस्पेस URI आप हल करना चाहते हैं। डिफ़ॉल्ट नेमस्पेस से मेल खाने के लिए, [String::Empty](../../../system/string/empty/) पास करें। |

### वापसी मान

एक [String](../../../system/string/) जो निर्दिष्ट नेमस्पेस उपसर्ग को सौंपा गया नेमस्पेस URI रखता है; यदि निर्दिष्ट उपसर्ग को कोई नेमस्पेस URI नहीं सौंपा गया है तो **nullptr**। लौटाया गया [String](../../../system/string/) एटॉमिक किया गया है।

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XPathNavigator](../)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)