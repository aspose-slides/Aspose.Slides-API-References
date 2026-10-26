---
title: Copy()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ाइल को निर्दिष्ट स्थान पर कॉपी करता है। यदि लक्ष्य फ़ाइल पहले से मौजूद है, तो एक पैरामीटर यह निर्धारित करता है कि उसे ओवरराइट किया जाना चाहिए या नहीं।
type: docs
weight: 40
url: /hi/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) मेथड

निर्दिष्ट फ़ाइल को निर्दिष्ट स्थान पर कॉपी करता है। यदि लक्ष्य फ़ाइल पहले से मौजूद है, तो एक पैरामीटर यह निर्धारित करता है कि उसे ओवरराइट किया जाना चाहिए या नहीं।

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | कॉपी करने वाली फ़ाइल का पथ |
| destFileName | const [String](../../../system/string/)\& | कॉपी की जाने वाली फ़ाइल के नए स्थान का पथ |
| overwrite | **bool** | यदि मौजूदा लक्ष्य फ़ाइल को ओवरराइट करना चाहिए तो true, यदि लक्ष्य फ़ाइल पहले से मौजूद है तो कॉपी विफल होनी चाहिए तो false |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [File](../)
* नामस्थान [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)