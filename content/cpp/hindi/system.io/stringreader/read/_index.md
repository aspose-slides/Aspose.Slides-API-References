---
title: Read()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्ट्रीम से एकल अक्षर पढ़ता है।
type: docs
weight: 40
url: /hi/system.io/stringreader/read/
---
## StringReader::Read() मेथड

स्ट्रीम से एक अक्षर पढ़ता है।

```cpp
virtual int System::IO::StringReader::Read() override
```

### रिटर्न वैल्यू

एक पढ़ा गया अक्षर या -1 यदि कोई अक्षर नहीं पढ़ा गया हो

## StringReader::Read(ArrayPtr\<char_t\>, int, int) मेथड

स्ट्रीम से निर्दिष्ट संख्या में अक्षरों को निर्दिष्ट स्थिति से शुरू करके निर्दिष्ट कैरेक्टर एरे में पढ़ता है।

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | स्ट्रीम से पढ़े गए अक्षरों को लिखने के लिए कैरेक्टर एरे |
| index | int | **buffer** में 0-आधारित इंडेक्स जहाँ से लिखना शुरू किया जाए |
| count | int | स्ट्रीम से पढ़े जाने वाले अक्षरों की संख्या |

### रिटर्न वैल्यू

स्ट्रीम से पढ़े गये अक्षरों की संख्या

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [StringReader](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)