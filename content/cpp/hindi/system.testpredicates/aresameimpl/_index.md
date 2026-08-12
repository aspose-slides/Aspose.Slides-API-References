---
title: AreSameImpl()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Are-same स्मार्ट पॉइंटर्स की तुलना करता है।
type: docs
weight: 79
url: /hi/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1&, const T2&, long long) फ़ंक्शन

Are-same स्मार्ट पॉइंटर्स की तुलना करता है।

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1& | LHS मान। |
| rhs | const T2& | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-styled assertion result.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1&, const T2&, long long) फ़ंक्शन

Are-same अपवादों की तुलना करता है।

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1& | LHS मान। |
| rhs | const T2& | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-styled assertion result.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1&, const T2&, int) फ़ंक्शन

Are-same नॉन-पॉइंटर मानों की तुलना करता है।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1& | LHS मान। |
| rhs | const T2& | RHS मान। |

### वापसी मान

gtest-styled assertion result.

## संबंधित देखें

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)