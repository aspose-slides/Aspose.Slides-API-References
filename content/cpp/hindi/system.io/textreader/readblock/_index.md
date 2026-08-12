---
title: ReadBlock()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: वर्तमान टेक्स्ट रीडर से निर्दिष्ट अधिकतम संख्या में अक्षरों को पढ़ता है और डेटा को एक बफ़र में लिखता है, जो निर्दिष्ट इंडेक्स से शुरू होता है।
type: docs
weight: 53
url: /hi/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) विधि

वर्तमान टेक्स्ट रीडर से निर्दिष्ट अधिकतम संख्या में अक्षरों को पढ़ता है और डेटा को buffer में लिखता है, जो निर्दिष्ट index से शुरू होता है।

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | पढ़े गए डेटा को लिखने के लिए एक अक्षर buffer |
| index | int | buffer में लिखना शुरू करने के लिए 0-आधारित index |
| count | int | पढ़ने के लिए अधिकतम अक्षरों की संख्या |

### वापसी मान

पढ़े गए अक्षरों की वास्तविक संख्या

## संबंधित देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [TextReader](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)