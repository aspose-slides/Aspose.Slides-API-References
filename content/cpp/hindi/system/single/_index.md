---
title: Single
second_title: C++ API संदर्भ के लिये Aspose.Slides
description: एकल-प्रिसीजन फ्लोटिंग पॉइंट संख्या के साथ काम करने के लिए विधियों को सम्मिलित करता है।
type: docs
weight: 1899
url: /hi/system/single/
---
## एकल स्ट्रक्ट

एकल-प्रिसीजन फ्लोटिंग पॉइंट संख्या के साथ काम करने के लिए विधियों को सम्मिलित करता है।

```cpp
class Single
```

## विधियां

| विधि | विवरण |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग, जिसमें किसी संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समतुल्य एकल-प्रिसीजन फ्लोटिंग पॉइंट मान में परिवर्तित करता है। |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट स्ट्रिंग, जिसमें किसी संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को प्रदान की गई फॉर्मेटिंग जानकारी का उपयोग करके समतुल्य एकल-प्रिसीजन फ्लोटिंग पॉइंट मान में परिवर्तित करता है। |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | निर्दिष्ट स्ट्रिंग, जिसमें किसी संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को प्रदान की गई फॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके समतुल्य एकल-प्रिसीजन फ्लोटिंग पॉइंट मान में परिवर्तित करता है। |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | निर्दिष्ट स्ट्रिंग, जिसमें किसी संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समतुल्य एकल-प्रिसीजन फ्लोटिंग पॉइंट मान में परिवर्तित करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | निर्दिष्ट स्ट्रिंग, जिसमें किसी संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को प्रदान की गई फॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके समतुल्य एकल-प्रिसीजन फ्लोटिंग पॉइंट मान में परिवर्तित करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | शून्य से बड़ा सबसे छोटा सकारात्मक मान। |
| static constexpr [MaxValue](./maxvalue/) | सबसे बड़ा संभव मान। |
| static constexpr [MinValue](./minvalue/) | सबसे छोटा संभव मान। |
| static constexpr [NaN](./nan/) | वह मान जो संख्या नहीं है। |
| static constexpr [NegativeInfinity](./negativeinfinity/) | ऋणात्मक अनंत। |
| static constexpr [PositiveInfinity](./positiveinfinity/) | धनात्मक अनंत। |

## संबंधित देखें

* नामस्थान [System](../)
* ग्रंथालय [Aspose.Slides](../../)