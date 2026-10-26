---
title: Char
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: UTF-16 कोड इकाइयों के रूप में प्रस्तुत अक्षरों को बदलने के लिए विधियों को प्रदान करता है। यह कोई इंस्टेंस सेवाएँ न रखने वाला एक स्थैतिक प्रकार है। इसे किसी भी माध्यम से इंस्टेंस नहीं बनाना चाहिए।
type: docs
weight: 170
url: /hi/system/char/
---
## Char वर्ग


UTF-16 कोड इकाइयों के रूप में प्रतिनिधित्व किए गए अक्षरों को बदलने के लिए विधियों को प्रदान करता है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं हैं। आपको इसे किसी भी माध्यम से इंस्टेंस नहीं बनानी चाहिए।

```cpp
class Char
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | UTF-32 कोड इकाई को [System::String](../string/) वर्ग की एक इंस्टेंस में बदलता है। |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | निर्दिष्ट UTF-16 सरोगेट जोड़े को UTF-32 कोड इकाई में बदलता है। |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | स्ट्रिंग में निर्दिष्ट स्थिति पर UTF-16 एन्कोडेड अक्षर या सरोगेट जोड़े के मान को UTF-32 कोड इकाई में बदलता है। |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | निर्दिष्ट UTF-16 अक्षर को डबल-प्रिसीजन फ़्लोटिंग-पॉइंट संख्यात्मक मान में बदलता है। |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | निर्दिष्ट अक्षर की यूनिकोड श्रेणी को दर्शाने वाला मान लौटाता है। |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को ASCII व्हाइटस्पेस अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर को यूनिकोड नियंत्रण अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsControl](./iscontrol/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को यूनिकोड नियंत्रण अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर को दशमलव अंक के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | निर्धारित करता है कि क्या निर्दिष्ट स्ट्रिंग में निर्दिष्ट सूचकांक पर अक्षर को दशमलव अंक के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsDigit](./isdigit/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को दशमलव अंक के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | निर्धारित करता है कि क्या निर्दिष्ट स्ट्रिंग में निर्दिष्ट सूचकांक पर अक्षर UTF-16 हाई सरोगेट कोड इकाई है। |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर एक हाई सरोगेट है। |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर एक हाई सरोगेट है। |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर को यूनिकोड अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsLetter](./isletter/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को यूनिकोड अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर को यूनिकोड अक्षर या दशमलव अंक के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को यूनिकोड अक्षर या दशमलव अंक के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsLower](./islower/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्धारित सूचकांक पर अक्षर को लोअर केस अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsLower](./islower/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को लोअर केस अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | निर्धारित करता है कि क्या निर्दिष्ट स्ट्रिंग में निर्दिष्ट सूचकांक पर अक्षर को लोअर केस अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर एक लो सरोगेट है। |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर एक लो सरोगेट है। |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर को संख्या के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsNumber](./isnumber/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को संख्या के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर को विराम चिह्न के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को विराम चिह्न के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर को विभाजक अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsSeparator](./isseparator/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को विभाजक अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर एक UTF-16 सरोगेट कोड इकाई है। |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | निर्धारित करता है कि क्या निर्दिष्ट स्ट्रिंग में निर्दिष्ट सूचकांक पर अक्षर UTF-16 सरोगेट कोड इकाई है। |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | निर्धारित करता है कि क्या दो निर्दिष्ट अक्षर एक UTF-16 सरोगेट जोड़े के लिए हैं। |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में दो क्रमिक अक्षर एक सरोगेट जोड़ा बनाते हैं। |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर को प्रतीक अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsSymbol](./issymbol/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को प्रतीक अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | निर्धारित करता है कि क्या निर्दिष्ट स्ट्रिंग में निर्दिष्ट सूचकांक पर अक्षर को अपर केस अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर को अपर केस अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsUpper](./isupper/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को अपर केस अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर बफ़र में निर्दिष्ट सूचकांक पर अक्षर को व्हाइटस्पेस अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | निर्धारित करता है कि क्या निर्दिष्ट अक्षर को व्हाइटस्पेस अक्षर के रूप में वर्गीकृत किया गया है। |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | निर्धारित करता है कि क्या निर्दिष्ट स्ट्रिंग में निर्दिष्ट सूचकांक पर अक्षर को व्हाइटस्पेस अक्षर के रूप में वर्गीकृत किया गया है। |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग के पहले और एकमात्र अक्षर को char_t मान में बदलता है। |
| static char_t [ToLower](./tolower/)(char_t) | निर्दिष्ट अक्षर को लोअर केस में बदलता है। |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | निर्दिष्ट अक्षर को लोअर केस में बदलता है। |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | निर्दिष्ट अक्षर को लोअर केस में बदलता है। |
| static char_t [ToUpper](./toupper/)(char_t) | निर्दिष्ट अक्षर को अपर केस में बदलता है। |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | निर्दिष्ट अक्षर को अपर केस में बदलता है। |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | निर्दिष्ट अक्षर को अपर केस में बदलता है। |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | एकल अक्षर वाली स्ट्रिंग को UTF-16 अक्षर में बदलने का प्रयास करता है। फ़ंक्शन तभी सफल होता है जब इनपुट स्ट्रिंग null न हो और उसकी लंबाई ठीक एक अक्षर हो। |

## देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)