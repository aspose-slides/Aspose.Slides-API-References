---
title: AreNotSameImpl()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Are-not-same स्मार्ट पॉइंटर्स की तुलना करता है।
type: docs
weight: 105
url: /hi/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) फ़ंक्शन

Are-not-same-compares स्मार्ट पॉइंटर्स।

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |
| s | long long | फ़ंक्शन के कार्यान्वयन के चयनकर्ता के रूप में कार्य करने वाला एक सर्विस पैरामीटर; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न मान

gtest-शैली वाला असर्शन परिणाम।

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) फ़ंक्शन

Are-not-same-compares नॉन-पॉइंटर वैल्यूज़।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |

### रिटर्न मान

gtest-शैली वाला असर्शन परिणाम।

## देखें भी

* स्ट्रक्ट [IsSmartPtr](../../system/issmartptr/)
* नेमस्पेस [System::TestPredicates](../)
* लाइब्रेरी [Aspose.Slides](../../)