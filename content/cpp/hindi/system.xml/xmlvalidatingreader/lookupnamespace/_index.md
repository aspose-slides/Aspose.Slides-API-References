---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान तत्व के दायरे में नेमस्पेस उपसर्ग को हल करता है।
type: docs
weight: 547
url: /hi/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) विधि

वर्तमान तत्व के दायरे में नेमस्पेस उपसर्ग को हल करता है।

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | वह उपसर्ग जिसकी नेमस्पेस यूनिफ़ॉर्म रिसोर्स आइडेंटिफ़ायर (URI) आप हल करना चाहते हैं। डिफ़ॉल्ट नेमस्पेस से मेल करने के लिए, एक खाली स्ट्रिंग पास करें। |

### लौटाया गया मान

उसी नेमस्पेस URI जिससे उपसर्ग मैप होता है या **nullptr** यदि कोई मेल खाने वाला उपसर्ग नहीं मिला।

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlValidatingReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)