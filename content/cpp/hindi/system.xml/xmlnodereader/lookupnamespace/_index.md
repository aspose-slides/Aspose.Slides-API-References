---
title: LookupNamespace()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: वर्तमान तत्व के स्कोप में नेमस्पेस प्रीफ़िक्स को हल करता है।
type: docs
weight: 404
url: /hi/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String&) method

वर्तमान तत्व के स्कोप में नेमस्पेस प्रीफ़िक्स को हल करता है।

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | वर्णन |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)& | वह प्रीफ़िक्स जिसका नेमस्पेस URI आप हल करना चाहते हैं। डिफ़ॉल्ट नेमस्पेस से मेल खाने के लिए, एक खाली स्ट्रिंग पास करें। इस स्ट्रिंग को एटॉमिक होने की आवश्यकता नहीं है। |

### वापसी मान

वह नेमस्पेस URI जिसके साथ प्रीफ़िक्स मैप किया जाता है या **nullptr** यदि कोई मिलता-जुलता प्रीफ़िक्स नहीं मिलता।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNodeReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)