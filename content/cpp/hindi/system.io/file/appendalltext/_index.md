---
title: AppendAllText()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट एन्कोडिंग का उपयोग करके निर्दिष्ट फ़ाइल में निर्दिष्ट स्ट्रिंग को जोड़ता है।
type: docs
weight: 14
url: /hi/system.io/file/appendalltext/
---
## File::AppendAllText(const String\&, const String\&, const EncodingPtr\&) मेथड

निर्दिष्ट एन्कोडिंग का उपयोग करके निर्दिष्ट फ़ाइल में निर्दिष्ट स्ट्रिंग को जोड़ता है।

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | स्ट्रिंग जोड़ने वाली फ़ाइल का पथ |
| contents | const [String](../../../system/string/)\& | फ़ाइल में लिखने के लिए स्ट्रिंग |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए अक्षर एन्कोडिंग |

## संबंधित देखें

* Typedef [EncodingPtr](../../../system/encodingptr/)
* क्लास [String](../../../system/string/)
* क्लास [File](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)