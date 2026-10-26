---
title: ComparerType
second_title: Aspose.Slides for C++ API संदर्भ
description: घटते क्रम के 'less' सेमांटिक्स का उपयोग करके तत्वों की तुलना करता है।
type: docs
weight: 144
url: /hi/system.collections.generic.details/comparertype/
---
## ComparerType संरचना

घटते क्रम के 'less' सेमांटिक्स का उपयोग करके तत्वों की तुलना करता है।

```cpp
template<typename T>class ComparerType
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | तुलना किए गए तत्वों का प्रकार। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [IComparable](../../system/icomparable/) इंटरफ़ेस को लागू करने वाले मान प्रकारों की तुलना करता है। |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | मूल मान प्रकारों और उन वस्तुओं की तुलना करता है जो [IComparable](../../system/icomparable/) इंटरफ़ेस को लागू नहीं करती हैं। |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | फ़्लोटिंग पॉइंट प्रकारों की तुलना करता है। |

## देखें

* नामस्थान [System::Collections::Generic::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)