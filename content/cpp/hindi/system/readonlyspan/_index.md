---
title: ReadOnlySpan
second_title: Aspose.Slides for C++ API संदर्भ
description: Span क्लास के भीतर उपयोग के लिए अग्रेषित.
type: docs
weight: 1210
url: /hi/system/readonlyspan/
---
## ReadOnlySpan क्लास


Forward to use within [Span](../span/) क्लास.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार। यह क्लास केवल-पढ़ने-योग्य तरीके से वस्तुओं के लगातार अनुक्रमों के साथ काम करने का टाइप-सेफ़ तरीका प्रदान करती है। इसे एरे, स्टैक एरे, या कच्चे पॉइंटर्स को रैप करने के लिए उपयोग किया जा सकता है जबकि बाउंड्स चैकिंग बनाए रखता है। [ReadOnlySpan](./) उस मेमोरी का मालिक नहीं है जिसे वह इंगित करता है - यह केवल मौजूदा मेमोरी का एक दृश्य है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | एक नियमित स्पैन से केवल-पढ़ने-योग्य स्पैन बनाता है। |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | एक एरे को [ReadOnlySpan](./) में परिवर्तित करता है। |
## टिप्पणियाँ

एक मनमाने मेमोरी के केवल-पढ़ने-योग्य निरन्तर क्षेत्र का प्रतिनिधित्व करता है।

## देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)