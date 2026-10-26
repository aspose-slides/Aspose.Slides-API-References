---
title: IntroSort()
second_title: Aspose.Slides for C++ API संदर्भ
description: कुंजी-मूल्य जोड़ों के लिए introsort एल्गोरिदम का आंतरिक कार्यान्वयन।
type: docs
weight: 40
url: /hi/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) फ़ंक्शन

कुंजी-मूल्य जोड़ों के लिए introsort एल्गोरिदम की आंतरिक कार्यान्वयन।

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कियों का प्रकार |
| TValue | मानों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | क्रमबद्ध करने के लिये कियों का स्पैन |
| values | [Span](../../system/span/)\<TValue\>\& | क्रमबद्ध करने के लिये मानों का स्पैन |
| depthLimit | **int32_t** | हीपसॉर्ट में स्विच करने से पहले अधिकतम पुनरावृत्ति गहराई |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) फ़ंक्शन कियों के लिये |

## देखें

* क्लास [Span](../../system/span/)
* नामस्थान [System::MemoryExtensions::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)