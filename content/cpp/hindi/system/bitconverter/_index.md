---
title: BitConverter
second_title: Aspose.Slides for C++ API संदर्भ
description: क्रमबद्ध बाइट्स को वैल्यू टाइप में और इसके विपरीत परिवर्तित करने वाले मेथड्स को सम्मिलित करता है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं हैं। आपको इस प्रकार की कोई भी इंस्टेंस कभी भी नहीं बनानी चाहिए।
type: docs
weight: 66
url: /hi/system/bitconverter/
---
## BitConverter क्लास

क्रमबद्ध बाइट्स को वैल्यू टाइप में और इसके विपरीत परिवर्तित करने वाले मेथड्स को सम्मिलित करता है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं हैं। आपको इस प्रकार की कोई भी इंस्टेंस कभी भी नहीं बनानी चाहिए।

```cpp
class BitConverter
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | वर्तमान आर्किटेक्चर की एंडियननेस को दर्शाता है। |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | निर्दिष्ट डबल-प्रेसिशन फ्लोटिंग पॉइंट मान की बाइनरी प्रतिनिधित्व के बराबर 64-बिट पूर्णांक मान लौटाता है। |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | निर्दिष्ट बूलियन मान को बाइट्स की एरे में परिवर्तित करता है। |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | निर्दिष्ट char_t मान को बाइट्स की एरे में परिवर्तित करता है। |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | निर्दिष्ट 16-बिट पूर्णांक मान को बाइट्स की एरे में परिवर्तित करता है। |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | निर्दिष्ट 32-बिट पूर्णांक मान को बाइट्स की एरे में परिवर्तित करता है। |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | निर्दिष्ट 64-बिट पूर्णांक मान को बाइट्स की एरे में परिवर्तित करता है। |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | निर्दिष्ट unsigned 16-बिट पूर्णांक मान को बाइट्स की एरे में परिवर्तित करता है। |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | निर्दिष्ट unsigned 32-बिट पूर्णांक मान को बाइट्स की एरे में परिवर्तित करता है। |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | निर्दिष्ट unsigned 64-बिट पूर्णांक मान को बाइट्स की एरे में परिवर्तित करता है। |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | निर्दिष्ट सिंगल-प्रेसिशन फ्लोटिंग-पॉइंट मान को बाइट्स की एरे में परिवर्तित करता है। |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | निर्दिष्ट डबल-प्रेसिशन फ्लोटिंग-पॉइंट मान को बाइट्स की एरे में परिवर्तित करता है। |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | निर्दिष्ट मान के बराबर डबल-प्रेसिशन फ्लोटिंग-पॉइंट मान लौटाता है। |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के एक बाइट को बूलियन मान में परिवर्तित करता है। |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के एक बाइट को बूलियन मान में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के दो बाइट को char_t मान में परिवर्तित करता है। |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के दो बाइट को char_t मान में परिवर्तित करता है। |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के आठ बाइट को डबल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है। |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के आठ बाइट को डबल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के दो बाइट को 16-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के दो बाइट को 16-बिट पूर्णांक मान में परिवर्तित करता है। |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के चार बाइट को 32-बिट पूर्णांक मान में परिवर्तित करता है। |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के चार बाइट को 32-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के आठ बाइट को 64-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के आठ बाइट को 64-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के चार बाइट को सिंगल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है। |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के चार बाइट को सिंगल-प्रेसिशन फ्लोटिंग-पॉइंट मान में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | निर्दिष्ट बाइट एरे के सभी मानों को उनकी हेक्साडेसिमल स्ट्रिंग निरूपण में परिवर्तित करता है। हेक्साडेसिमल नोटेशन में अक्षरों के केस और प्रत्येक आसन्न बाइट जोड़े के बीच डाले जाने वाले विभाजक को संबंधित आर्ग्यूमेंट्स द्वारा निर्दिष्ट किया जाता है। |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए निर्दिष्ट बाइट एरे के मानों को उनकी हेक्साडेसिमल स्ट्रिंग निरूपण में परिवर्तित करता है। |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | निर्दिष्ट बाइट एरे के मानों की एक रेंज को उनकी हेक्साडेसिमल स्ट्रिंग निरूपण में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के दो बाइट को unsigned 16-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के दो बाइट को unsigned 16-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के चार बाइट को unsigned 32-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के चार बाइट को unsigned 32-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के आठ बाइट को unsigned 64-बिट पूर्णांक मान में परिवर्तित करता है। |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | निर्दिष्ट इंडेक्स से शुरू होते हुए एरे के आठ बाइट को unsigned 64-बिट पूर्णांक मान में परिवर्तित करता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | वर्तमान आर्किटेक्चर की एंडियननेस को दर्शाता है। यदि आर्किटेक्चर लिटिल एंडियन है तो true, अन्यथा false। |

## टिप्पणी



```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // प्रिंट करने के लिए मान बनाएं.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // मान और उसके बाइट्स को प्रिंट करें.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)