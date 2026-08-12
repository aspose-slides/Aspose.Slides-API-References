---
title: WriteAllText()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नई टेक्स्ट फ़ाइल बनाता है या मौजूदा को अधिलेखित करता है और निर्दिष्ट एन्कोडिंग का उपयोग करके निर्दिष्ट स्ट्रिंग की सामग्री को उसमें लिखता है।
type: docs
weight: 469
url: /hi/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) मेथड

नया टेक्स्ट फ़ाइल बनाता है या मौजूदा को अधिलेखित करता है और निर्दिष्ट एन्कोडिंग का उपयोग करके निर्दिष्ट स्ट्रिंग की सामग्री को उसमें लिखता है।

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | बनाने या अधिलेखित करने के लिये फ़ाइल |
| contents | const [String](../../../system/string/)\& | एक स्ट्रिंग सरणी |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | उपयोग करने के लिये कैरेक्टर एन्कोडिंग |

## संबंधित देखें

* Typedef [EncodingPtr](../../../system/encodingptr/)
* क्‍लास [String](../../../system/string/)
* क्‍लास [File](../)
* नामस्थान [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)