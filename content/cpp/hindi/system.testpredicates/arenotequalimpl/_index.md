---
title: AreNotEqualImpl()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: असमान-तुलना उन मानों की होती है जहाँ एक या दोनों Decimal होते हैं।
type: docs
weight: 53
url: /hi/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) फ़ंक्शन

समान-नहीं तुलना उन मानों की होती है जहाँ एक या दोनों [Decimal](../../system/decimal/) होते हैं।

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन को चयन करने के लिए उपयोग किया जाता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली की अभिकथन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) फ़ंक्शन

समान-नहीं तुलना दो [System::String](../../system/string/) मानों की होती है, जो नल [String](../../system/string/) पर सदस्य फ़ंक्शन को बुलाने से बचाती है। AreEqualImpl [String](../../system/string/) के ओवरलोड जैसी ही deductive-आधारित बहिष्कार कारणों के लिए टेम्पलेट किया गया है।

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार, [System::String](../../system/string/) तक सीमित। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T\& | LHS मान। |
| rhs | const T\& | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन को चयन करने के लिए उपयोग किया जाता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली की अभिकथन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) फ़ंक्शन

समान-नहीं तुलना non-pointer प्रकारों की प्रदान की गई Equals विधि का उपयोग करके होती है।

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T\& | LHS मान। |
| rhs | const T\& | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन को चयन करने के लिए उपयोग किया जाता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली की अभिकथन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) फ़ंक्शन

समान-नहीं तुलना non-pointer प्रकारों की प्रदान की गई Equals विधि का उपयोग करके होती है।

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T\& | LHS मान। |
| rhs | const T\& | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन को चयन करने के लिए उपयोग किया जाता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली की अभिकथन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) फ़ंक्शन

समान-नहीं तुलना non-pointer प्रकारों की operator != प्रदान किए जाने से होती है।

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T\& | LHS मान। |
| rhs | const T\& | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन को चयन करने के लिए उपयोग किया जाता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली की अभिकथन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) फ़ंक्शन

समान-नहीं तुलना बॉक्सेबल को [SmartPtr](../../system/smartptr/) मानों के साथ अनबॉक्सिंग का उपयोग करके करती है।

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T | LHS मान। |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन को चयन करने के लिए उपयोग किया जाता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली की अभिकथन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) फ़ंक्शन

समान-नहीं तुलना बॉक्सेबल को [SmartPtr](../../system/smartptr/) मानों के साथ अनबॉक्सिंग का उपयोग करके करती है।

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS मान। |
| rhs | T | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन को चयन करने के लिए उपयोग किया जाता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली की अभिकथन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) फ़ंक्शन

समान-नहीं तुलना यादृच्छिक प्रकार को nullptr के साथ करती है।

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T | LHS मान। |
| s | std::nullptr_t | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन को चयन करने के लिए उपयोग किया जाता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली की अभिकथन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) फ़ंक्शन

समान-नहीं तुलना यादृच्छिक प्रकार को nullptr के साथ करती है।

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| rhs | std::nullptr_t | RHS मान। |
| s | T | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन को चयन करने के लिए उपयोग किया जाता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली की अभिकथन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) फ़ंक्शन

Equal-तुलना पॉइंटर प्रकारों की होती है।

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS प्रकार। |
| T2 | RHS प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन को चयन करने के लिए उपयोग किया जाता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली की अभिकथन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) फ़ंक्शन

Equal-तुलना यादृच्छिक प्रकारों की gtest अल्गोरिद्म का उपयोग करके होती है।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS प्रकार। |
| T2 | RHS प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्षा। |
| rhs_expr | const char * | RHS अभिव्यक्षा। |
| lhs | T1 | LHS मान। |
| rhs | T2 | RHS मान। |

### वापसी मान

gtest-शैली की अभिकथन परिणाम।

## देखें

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)