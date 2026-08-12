---
title: Read()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्ट्रीम से एकल अक्षर पढ़ता है।
type: docs
weight: 40
url: /hi/system.io/streamreader/read/
---
## StreamReader::Read() method

स्ट्रीम से एकल अक्षर पढ़ता है।

```cpp
virtual int System::IO::StreamReader::Read() override
```

### Return Value

UTF-16 एन्कोडिंग के साथ एन्कोड किया गया अक्षर पढ़ता है; यदि पढ़ा गया अक्षर UTF-16 एन्कोडिंग में दो कोडपॉइंट्स द्वारा प्रतिनिधित्व करता है तो केवल उच्च सर्रगेट वापस किया जाता है।

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) method

स्ट्रीम से निर्दिष्ट संख्या में अक्षर पढ़ता है, उन्हें UTF-16 एन्कोडिंग में परिवर्तित करता है और परिणामस्वरूप UTF-16 अक्षरों को निर्दिष्ट स्थिति से शुरू करके निर्दिष्ट अक्षर एरे में लिखता है।

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | स्ट्रीम से पढ़े गए अक्षरों को लिखने के लिए UTF-16 अक्षर एरे |
| index | int | **buffer** में 0-आधारित इंडेक्स जहाँ से लिखना शुरू करना है |
| count | int | स्ट्रीम से पढ़ने के लिये अक्षरों की संख्या |

### Return Value

स्ट्रीम से पढ़े गए अक्षरों की संख्या

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [StreamReader](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)