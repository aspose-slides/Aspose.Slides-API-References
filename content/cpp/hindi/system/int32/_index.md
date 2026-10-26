---
title: Int32
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: 32-बिट पूर्णांक के साथ काम करने के लिए विधियों को समाहित करता है।
type: docs
weight: 1041
url: /hi/system/int32/
---
## Int32 क्लास

32-बिट पूर्णांक के साथ काम करने के लिए विधियों को समाहित करता है।

```cpp
class Int32
```

## विधियां

| विधि | विवरण |
| --- | --- |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग को जो किसी संख्या की स्ट्रिंग प्रतिनिधित्व रखती है, को संगत 32-बिट साइन्ड पूर्णांक में परिवर्तित करता है। |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट स्ट्रिंग को जो किसी संख्या की स्ट्रिंग प्रतिनिधित्व रखती है, प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके संगत 32-बिट साइन्ड पूर्णांक में परिवर्तित करता है। |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी और नंबर शैली का उपयोग करके निर्दिष्ट स्ट्रिंग को जो किसी संख्या की स्ट्रिंग प्रतिनिधित्व रखती है, संगत 32-बिट साइन्ड पूर्णांक में परिवर्तित करता है। |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int32_t**\&) | निर्दिष्ट स्ट्रिंग को जो किसी संख्या की स्ट्रिंग प्रतिनिधित्व रखती है, को संगत 32-बिट साइन्ड पूर्णांक में परिवर्तित करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int32_t**\&) | प्रदान की गई फ़ॉर्मेटिंग जानकारी और नंबर शैली का उपयोग करके निर्दिष्ट स्ट्रिंग को जो किसी संख्या की स्ट्रिंग प्रतिनिधित्व रखती है, संगत 32-बिट साइन्ड पूर्णांक में परिवर्तित करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int32_t**\&) |  |

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | संभव सबसे बड़ा मान। |
| static constexpr [MinValue](./minvalue/) | संभव सबसे छोटा मान। |

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)