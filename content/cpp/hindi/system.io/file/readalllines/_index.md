---
title: ReadAllLines()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट टेक्स्ट फ़ाइल की सामग्री को लाइन दर लाइन स्ट्रिंग्स की एरे में पढ़ता है, निर्दिष्ट अक्षर एन्कोडिंग का उपयोग करके।
type: docs
weight: 300
url: /hi/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) मेथड


निर्दिष्ट टेक्स्ट फ़ाइल की सामग्री को लाइन दर लाइन स्ट्रिंग्स की एक एरे में पढ़ता है, निर्दिष्ट अक्षर एन्कोडिंग का उपयोग करके।

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | फ़ाइल को पढ़ने के लिए पथ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए अक्षर एन्कोडिंग |

### रिटर्न वैल्यू

एक स्ट्रिंग एरे जिसमें प्रत्येक तत्व निर्दिष्ट फ़ाइल की एकल लाइन का प्रतिनिधित्व करता है।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* क्लास [String](../../../system/string/)
* क्लास [File](../)
* नेमस्पेस [System::IO](../../)
* Library [Aspose.Slides](../../../)