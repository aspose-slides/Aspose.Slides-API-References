---
title: ReadAllText()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट टेक्स्ट फ़ाइल की सामग्री को निर्दिष्ट कैरेक्टर एन्कोडिंग का उपयोग करके एकल String ऑब्जेक्ट में पढ़ता है।
type: docs
weight: 313
url: /hi/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) विधि

निर्दिष्ट टेक्स्ट फ़ाइल की सामग्री को निर्दिष्ट कैरेक्टर एन्कोडिंग का उपयोग करके एकल [String](../../../system/string/) ऑब्जेक्ट में पढ़ता है।

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Arguments

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | फ़ाइल को पढ़ने के लिए पथ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिए कैरेक्टर एन्कोडिंग |

### Return Value

एक string जिसमें निर्दिष्ट फ़ाइल की सामग्री होती है

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* क्लास [String](../../../system/string/)
* क्लास [File](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)