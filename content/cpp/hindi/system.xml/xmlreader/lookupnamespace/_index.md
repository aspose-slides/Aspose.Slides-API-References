---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब इसे एक व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो यह वर्तमान तत्व के स्कोप में नेमस्पेस प्रीफ़िक्स को हल करता है।
type: docs
weight: 729
url: /hi/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) method


जब इसे एक व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो यह वर्तमान तत्व के स्कोप में नेमस्पेस प्रीफ़िक्स को हल करता है।

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | उस प्रीफ़िक्स का नेमस्पेस URI जिसे आप हल करना चाहते हैं। डिफ़ॉल्ट नेमस्पेस से मेल खाने के लिए, एक खाली स्ट्रिंग पास करें। |

### वापसी मान

वह नेमस्पेस URI जिससे प्रीफ़िक्स मैप होता है या **nullptr** अगर कोई मिलता हुआ प्रीफ़िक्स नहीं मिलता।

## संबंधित देखें

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)