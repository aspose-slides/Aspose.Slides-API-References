---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट करता है कि स्ट्रिंग और DateTime के बीच रूपांतरण के समय समय मान को कैसे संभालना है।
type: docs
weight: 781
url: /hi/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

निर्दिष्ट करता है कि स्ट्रिंग और [DateTime](../../system/datetime/) के बीच रूपांतरण के समय समय मान को कैसे संभालना है।

```cpp
enum class XmlDateTimeSerializationMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Local | 0 | स्थानीय समय के रूप में माना जाता है। यदि [DateTime](../../system/datetime/) ऑब्जेक्ट समन्वित सार्वभौमिक समय (UTC) का प्रतिनिधित्व करता है, तो इसे स्थानीय समय में परिवर्तित किया जाता है। |
| Utc | 1 | UTC के रूप में माना जाता है। यदि [DateTime](../../system/datetime/) ऑब्जेक्ट स्थानीय समय का प्रतिनिधित्व करता है, तो इसे UTC में परिवर्तित किया जाता है। |
| Unspecified | 2 | यदि [DateTime](../../system/datetime/) को स्ट्रिंग में रूपांतरित किया जा रहा हो तो इसे स्थानीय समय के रूप में माना जाता है। यदि स्ट्रिंग को [DateTime](../../system/datetime/) में रूपांतरित किया जा रहा हो, तो यदि टाइम ज़ोन निर्दिष्ट किया गया हो तो स्थानीय समय में परिवर्तित करें। |
| RoundtripKind | 3 | रूपांतरण के समय टाइम ज़ोन जानकारी को सुरक्षित रखना चाहिए। |

## देखें

* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)