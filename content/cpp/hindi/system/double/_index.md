---
title: Double
second_title: Aspose.Slides for C++ API संदर्भ
description: डबल-प्रिसीजन फ्लोटिंग-पॉइंट संख्या के साथ काम करने के लिए मेथड्स शामिल हैं।
type: docs
weight: 1574
url: /hi/system/double/
---
## डबल स्ट्रक्ट

डबल-प्रिसीजन फ्लोटिंग-पॉइंट संख्या के साथ काम करने के लिए मेथड्स शामिल हैं।

```cpp
class Double
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information and number style. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information and number style. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | शून्य से बड़ा सबसे छोटा सकारात्मक मान। |
| static constexpr [MaxValue](./maxvalue/) | संभाव्य सबसे बड़ा मान। |
| static constexpr [MinValue](./minvalue/) | संभाव्य सबसे छोटा मान। |
| static constexpr [NaN](./nan/) | संख्या नहीं है। |
| static constexpr [NegativeInfinity](./negativeinfinity/) | नकारात्मक अनंत। |
| static constexpr [PositiveInfinity](./positiveinfinity/) | धनात्मक अनंत। |

## संदर्भ

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)