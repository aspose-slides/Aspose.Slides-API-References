---
title: Read()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: स्ट्रीम से एकल अक्षर पढ़ता है।
type: docs
weight: 40
url: /hi/system.io/textreader/read/
---
## TextReader::Read() विधि

स्ट्रीम से एकल अक्षर पढ़ता है।

```cpp
virtual int System::IO::TextReader::Read()
```

### रिटर्न मान

UTF-16 एन्कोडिंग के साथ एन्कोड किया गया अक्षर पढ़ता है; यदि पढ़ा गया अक्षर UTF-16 एन्कोडिंग में दो कोडपॉइंट्स द्वारा प्रतिनिधित्व किया गया है तो केवल उच्च सरगेट वापस किया जाता है।

## TextReader::Read(ArrayPtr\<char_t\>, int, int) विधि

स्ट्रीम से निर्दिष्ट संख्या में अक्षर पढ़ता है और उन्हें निर्दिष्ट स्थिति से शुरू होकर निर्दिष्ट अक्षर एरे में लिखता है।

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | स्ट्रीम से पढ़े गए अक्षरों को लिखने के लिए UTF-16 अक्षर एरे |
| index | int | **buffer** में 0-आधारित इंडेक्स जिस स्थान से लिखना शुरू करना है |
| count | int | स्ट्रीम से पढ़े जाने वाले अक्षरों की संख्या |

### रिटर्न मान

स्ट्रीम से पढ़े गए अक्षरों की संख्या

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [TextReader](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)