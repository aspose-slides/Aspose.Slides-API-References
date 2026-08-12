---
title: Span
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक निरंतर मेमोरी क्षेत्र का प्रतिनिधित्व करता है जो C++20 के std::span के समान है।"
type: docs
weight: 1262
url: /hi/system/span/
---
## Span वर्ग

Arbitrary memory के अपरिवर्तनीय क्रम के समान C++20 के std::span की तरह एक निरंतर मेमोरी क्षेत्र का प्रतिनिधित्व करता है।

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | Span में तत्वों का प्रकार। यह वर्ग वस्तुओं की निरंतर अनुक्रमों के साथ काम करने का प्रकार-सुरक्षित तरीका प्रदान करता है। इसे एरे, स्टैक एरे, या कच्चे पॉइंटर्स को लपेटने के लिए उपयोग किया जा सकता है जबकि सीमा जाँच को बनाए रखता है। The [Span](./) मेमोरी का स्वामित्व नहीं रखता जो यह इंगित करता है - यह केवल मौजूदा मेमोरी का एक दृश्य है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [Clear](./clear/)() const | सभी तत्वों को डिफ़ॉल्ट मान पर सेट करके Span की सामग्री को साफ़ करता है। |
| void [Fill](./fill/)(const T\&) const | निर्दिष्ट मान के साथ Span को भरता है। |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | एक एरे को [Span](./) में बदलता है। |

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)