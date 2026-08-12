---
title: ComparerAdapter
second_title: Aspose.Slides for C++ API संदर्भ
description: STL पर्यावरण में IComparer का उपयोग करने के लिए एडेप्टर। यदि सेट हो तो IComparer का उपयोग करता है; अन्यथा, यदि उपलब्ध हो तो operator < का उपयोग करता है या (यदि नहीं) false लौटाता है।
type: docs
weight: 638
url: /hi/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

Adapter to use [IComparer](../icomparer/) within STL environment. Uses [IComparer](../icomparer/) if set; otherwise, uses operator < (if available) or returns false (if not).

```cpp
template<class T>class ComparerAdapter
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | तुलना किया जा रहा प्रकार। |
## विधियाँ

| मेथड | विवरण |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | बिना किसी उपलब्ध तुलनाकार के एडेप्टर बनाता है। |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | एडेप्टर बनाता है। |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) फ़ंक्शन उन प्रकारों के लिए जिनके पास operator < उपलब्ध है। |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) फ़ंक्शन उन प्रकारों के लिए जिनके पास operator < उपलब्ध नहीं है। |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | तुलनाकार ऑब्जेक्ट सेट करता है। |

## संबंधित देखें

* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)