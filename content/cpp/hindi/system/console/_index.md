---
title: Console
second_title: Aspose.Slides for C++ API संदर्भ
description: डेटा को मानक आउटपुट स्ट्रीम में आउटपुट करने के लिए मेथड प्रदान करता है। यह एक स्थैतिक प्रकार है जिसके पास कोई इंस्टेंस सेवाएँ नहीं हैं। आपको इसे किसी भी तरह से इंस्टेंस नहीं बनाना चाहिए।
type: docs
weight: 196
url: /hi/system/console/
---
## Console क्लास

डेटा को मानक आउटपुट स्ट्रीम में आउटपुट करने के लिए मेथड प्रदान करता है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएं नहीं हैं। आपको इसे किसी भी तरीके से इंस्टेंस नहीं बनाना चाहिए।

```cpp
class Console
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| static void [Beep](./beep/)() | अभी लागू नहीं किया गया। |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | एक साझा पॉइंटर लौटाता है जो उस ऑब्जेक्ट की ओर संकेत करता है जो मानक त्रुटि स्ट्रीम का प्रतिनिधित्व करता है। |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | एक साझा पॉइंटर लौटाता है जो उस ऑब्जेक्ट की ओर संकेत करता है जो मानक इनपुट स्ट्रीम का प्रतिनिधित्व करता है। |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | एक साझा पॉइंटर लौटाता है जो उस ऑब्जेक्ट की ओर संकेत करता है जो मानक आउटपुट स्ट्रीम का प्रतिनिधित्व करता है। |
| static void [Mute](./mute/)(**bool**) | मानक आउटपुट स्ट्रीम को म्यूट या अनम्यूट करता है। |
| static void [ReadKey](./readkey/)() | अभी लागू नहीं किया गया। |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | कंसोल विंडो कैप्शन सेट करता है। |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | निर्दिष्ट ऑब्जेक्ट को क्लास की Error प्रॉपर्टी में असाइन करता है। |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | In प्रॉपर्टी को निर्दिष्ट TextReader ऑब्जेक्ट पर सेट करता है। |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | निर्दिष्ट ऑब्जेक्ट को क्लास की Out प्रॉपर्टी में असाइन करता है। |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | निर्दिष्ट ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(**bool**) | bool मान का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(char_t) | निर्दिष्ट कैरेक्टर मान को मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | निर्दिष्ट कैरेक्टर ऐरे का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | [Decimal](../decimal/) मान का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(**double**) | double-precision फ्लोटिंग-पॉइंट मान का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(**float**) | single-precision फ्लोटिंग-पॉइंट मान का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(**int32_t**) | 32-बिट इंटीजर मान का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(**int64_t**) | 64-बिट इंटीजर मान का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग ऑब्जेक्ट को मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(const char_t *) | निर्दिष्ट c-स्ट्रिंग को मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | [TypeInfo](../typeinfo/) मान का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(**uint32_t**) | unsigned 32-बिट इंटीजर मान का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(**uint64_t**) | unsigned 64-बिट इंटीजर मान का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | निर्दिष्ट कैरेक्टर ऐरे की निर्दिष्ट रेंज का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | निर्दिष्ट फ़ॉर्मेट के अनुसार फ़ॉर्मेट किए गए निर्दिष्ट तर्कों का स्ट्रिंग प्रतिनिधित्व मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | वर्तमान लाइन टर्मिनेटर को मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | निर्दिष्ट ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(**bool**) | bool मान का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(char_t) | निर्दिष्ट कैरेक्टर मान को वर्तमान लाइन टर्मिनेटर के साथ मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | निर्दिष्ट कैरेक्टर ऐरे का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | [Decimal](../decimal/) मान का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(**double**) | double-precision फ्लोटिंग-पॉइंट मान का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(**float**) | single-precision फ्लोटिंग-पॉइंट मान का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(**int32_t**) | 32-बिट इंटीजर मान का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(**int64_t**) | 64-बिट इंटीजर मान का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग ऑब्जेक्ट को वर्तमान लाइन टर्मिनेटर के साथ मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(const char_t *) | निर्दिष्ट c-स्ट्रिंग को वर्तमान लाइन टर्मिनेटर के साथ मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | [TypeInfo](../typeinfo/) मान का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(**uint32_t**) | unsigned 32-बिट इंटीजर मान का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(**uint64_t**) | unsigned 64-बिट इंटीजर मान का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | निर्दिष्ट कैरेक्टर ऐरे की निर्दिष्ट रेंज का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | निर्दिष्ट Exception ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | निर्दिष्ट फ़ॉर्मेट के अनुसार फ़ॉर्मेट किए गए निर्दिष्ट तर्कों का स्ट्रिंग प्रतिनिधित्व, उसके बाद वर्तमान लाइन टर्मिनेटर के साथ, मानक आउटपुट स्ट्रीम पर आउटपुट करता है। |
| static void [WriteLine](./writeline/)(const char *) |  |

## टिप्पणी



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Hello संदेश को प्रिंट करें।
  Console::WriteLine(u"Hello, world!");

  // 'std::array' क्लास का एक इंस्टेंस बनाएं।
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // एरे के तत्वों को प्रिंट करें।
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
Hello, world!
1 2 3 4 5
*/
```

## देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)