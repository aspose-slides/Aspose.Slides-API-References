---
title: OpenText()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट मौजूदा फ़ाइल को UTF-8 एन्कोडिंग का उपयोग करके बिना शेयरिंग के टेक्स्ट पढ़ने हेतु खोलता है।
type: docs
weight: 261
url: /hi/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) विधि

निर्दिष्ट मौजूदा फ़ाइल को UTF-8 एन्कोडिंग का उपयोग करके बिना शेयरिंग के टेक्स्ट पढ़ने के लिए खोलता है।

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | फ़ाइल खोलने के पथ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए अक्षर एन्कोडिंग |

### रिटर्न मान

खोली गई फ़ाइल से जुड़ा एक [StreamWriter](../../streamwriter/) ऑब्जेक्ट का साझा पॉइंटर

## साथ ही देखें

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* क्लास [String](../../../system/string/)
* क्लास [File](../)
* नेमस्पेस [System::IO](../../)
* Library [Aspose.Slides](../../../)