---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान तत्व के दायरे में नेमस्पेस उपसर्ग को हल करता है।
type: docs
weight: 612
url: /hi/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) विधि

वर्तमान तत्व के दायरे में नेमस्पेस उपसर्ग को हल करता है।

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | वह उपसर्ग जिसका नेमस्पेस URI आप हल करना चाहते हैं। डिफ़ॉल्ट नेमस्पेस से मेल खाने के लिए, खाली स्ट्रिंग पास करें। इस स्ट्रिंग को एटॉमाइज़ करने की आवश्यकता नहीं है। |

### वापसी मान

वह नेमस्पेस URI जिससे उपसर्ग मानचित्रित होता है या **nullptr** यदि कोई मेल खाने वाला उपसर्ग नहीं मिलता।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlTextReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)