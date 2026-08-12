---
title: MemoryMarshal
second_title: Aspose.Slides for C++ API संदर्भ
description: मेमोरी मार्शलिंग कार्यान्वयन प्रदान करता है। केवल अनुवादित कोड के साथ संगतता के लिए, क्योंकि C++ पक्ष पर कोई प्रबंधित कोड समर्थित नहीं है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं हैं। इसे किसी भी तरीके से कभी भी इंस्टेंस नहीं बनाना चाहिए।
type: docs
weight: 27
url: /hi/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal क्लास

मेमोरी मार्शलिंग कार्यान्वयन प्रदान करता है। केवल अनुवादित कोड के साथ संगतता के लिए, क्योंकि C++ पक्ष पर कोई प्रबंधित कोड समर्थित नहीं है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं हैं। इसे किसी भी तरीके से कभी भी इंस्टेंस नहीं बनाना चाहिए।

```cpp
class MemoryMarshal
```

## विधियां

| विधि | विवरण |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | एक मूलभूत प्रकार T के एक [Span](../../system/span/) को बाइट्स के [Span](../../system/span/) में कास्ट करता है। |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | एक मूलभूत प्रकार TFrom के एक [Span](../../system/span/) को दूसरे मूलभूत प्रकार TTo में कास्ट करता है। |

## संबंधित देखें

* नामस्थान [System::Runtime::InteropServices](../)
* लाइब्रेरी [Aspose.Slides](../../)