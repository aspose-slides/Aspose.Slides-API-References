---
title: Byte
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: असाइनड 8-बिट पूर्णांक के साथ काम करने के लिए विधियों को सम्मिलित करता है।
type: docs
weight: 157
url: /hi/system/byte/
---
## Byte वर्ग

असाइनड 8-बिट पूर्णांक के साथ काम करने के लिए विधियों को शामिल करता है।

```cpp
class Byte
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग जो एक संख्या की स्ट्रिंग प्रतिनिधित्व रखती है, को समकक्ष 8-बिट असाइनड पूर्णांक में परिवर्तित करता है। |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट स्ट्रिंग जो एक संख्या की स्ट्रिंग प्रतिनिधित्व रखती है, को प्रदान की गई स्वरूपण जानकारी का उपयोग करके समकक्ष 8-बिट असाइनड पूर्णांक में परिवर्तित करता है। |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट स्ट्रिंग जो एक संख्या की स्ट्रिंग प्रतिनिधित्व रखती है, को प्रदान की गई स्वरूपण जानकारी और संख्या शैली का उपयोग करके समकक्ष 8-बिट असाइनड पूर्णांक में परिवर्तित करता है। |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint8_t**\&) | निर्दिष्ट स्ट्रिंग जो एक संख्या की स्ट्रिंग प्रतिनिधित्व रखती है, को समकक्ष 8-बिट असाइनड पूर्णांक में परिवर्तित करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint8_t**\&) | प्रदान की गई स्वरूपण जानकारी और संख्या शैली का उपयोग करके निर्दिष्ट स्ट्रिंग को समकक्ष 8-बिट असाइनड पूर्णांक में परिवर्तित करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint8_t**\&) |  |

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | संभावित सबसे बड़ा मान। |
| static constexpr [MinValue](./minvalue/) | संभावित सबसे छोटा मान। |

## टिप्पणियाँ



```cpp
#include <system/byte.h>

using namespace System;

int main()
{
  auto b1 = Byte::Parse(u"123");
  std::cout << static_cast<uint32_t>(b1) << std::endl;

  try
  {
    auto b2 = Byte::Parse(u"345");
    std::cout << static_cast<uint32_t>(b2) << std::endl;
  }
  catch (const OverflowException &ex)
  {
    std::cerr << ex.what() << std::endl;
  }

  uint8_t b3 = 0;
  if (Byte::TryParse(u"10", b3))
  {
    std::cout << static_cast<uint32_t>(b3) << std::endl;
  }
  else
  {
    std::cerr << "Something went wrong." << std::endl;
  }

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
123
System::OverflowException: मान या तो UInt8 के लिए बहुत बड़ा या बहुत छोटा था
10
*/
```

## संबंधित देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)