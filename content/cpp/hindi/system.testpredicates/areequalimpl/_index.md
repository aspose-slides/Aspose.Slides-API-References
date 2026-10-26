---
title: AreEqualImpl()
second_title: Aspose.Slides for C++ API संदर्भ
description: फ़्लोटिंग पॉइंट को arithmetic प्रकारों के साथ बराबर-तुलना करता है।
type: docs
weight: 27
url: /hi/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) फ़ंक्शन

फ़्लोटिंग पॉइंट को arithmetic प्रकारों के साथ बराबर-तुलना करता है।

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1 | LHS मान। |
| rhs | const T2 | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) फ़ंक्शन

एक या दोनों मान [Decimal](../../system/decimal/) होने पर बराबर-तुलना करता है।

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1& | LHS मान। |
| rhs | const T2& | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) फ़ंक्शन

प्रदान किए गए Equals मेथड का उपयोग करके नॉन-पॉइंटर प्रकारों की बराबर-तुलना करता है।

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T& | LHS मान। |
| rhs | const T& | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, T&, const T&, long long) फ़ंक्शन

प्रदान किए गए Equals मेथड का उपयोग करके नॉन-पॉइंटर प्रकारों की बराबर-तुलना करता है।

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T& | LHS मान। |
| rhs | const T& | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) फ़ंक्शन

प्रदान किए गए `operator ==` का उपयोग करके नॉन-पॉइंटर प्रकारों की बराबर-तुलना करता है।

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T& | LHS मान। |
| rhs | const T& | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>&, long long) फ़ंक्शन

[SmartPtr](../../system/smartptr/) मानों के साथ बॉक्सेबल की बराबर-तुलना करता है।

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T | LHS मान। |
| rhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>&, T, long long) फ़ंक्शन

[SmartPtr](../../system/smartptr/) मानों के साथ बॉक्सेबल की बराबर-तुलना करता है।

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | LHS मान। |
| rhs | T | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>&, long long) फ़ंक्शन

अनबॉक्सिंग के साथ [SmartPtr](../../system/smartptr/) मानों के साथ स्ट्रिंग लिटरल की बराबर-तुलना करता है।

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const char16_t * | LHS मान। |
| rhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>&, const char16_t *, long long) फ़ंक्शन

अनबॉक्सिंग के साथ [SmartPtr](../../system/smartptr/) मानों के साथ स्ट्रिंग लिटरल की बराबर-तुलना करता है।

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | LHS मान। |
| rhs | const char16_t * | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) फ़ंक्शन

रैंडम प्रकार को nullptr के साथ बराबर-तुलना करता है।

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T | LHS मान। |
| s | std::nullptr_t | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) फ़ंक्शन

रैंडम प्रकार को nullptr के साथ बराबर-तुलना करता है।

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| rhs | std::nullptr_t | RHS मान। |
| s | T | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) फ़ंक्शन

पॉइंटर प्रकारों की बराबर-तुलना करता है।

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS प्रकार। |
| T2 | RHS प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1& | LHS मान। |
| rhs | const T2& | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) फ़ंक्शन

पॉइंटर प्रकारों की बराबर-तुलना करता है।

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS प्रकार। |
| T2 | RHS प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1& | LHS मान। |
| rhs | const T2& | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable<T2>&, long long) फ़ंक्शन

[Nullable](../../system/nullable/) मान के साथ एक रैंडम प्रकार की बराबर-तुलना करता है।

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS प्रकार। |
| T2 | RHS प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T1 | LHS मान। |
| rhs | const [Nullable](../../system/nullable/)<T2>& | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable<T1>&, T2, long long) फ़ंक्शन

[Nullable](../../system/nullable/) मान के साथ एक रैंडम प्रकार की बराबर-तुलना करता है।

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS प्रकार। |
| T2 | RHS प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const [Nullable](../../system/nullable/)<T1>& | LHS मान। |
| rhs | T2 | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) फ़ंक्शन

gtest एल्गोरिद्म का उपयोग करके रैंडम प्रकारों की बराबर-तुलना करता है।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS प्रकार। |
| T2 | RHS प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T1 | LHS मान। |
| rhs | T2 | RHS मान। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) फ़ंक्शन

दो [System::String](../../system/string/) मानों की बराबर-तुलना करता है, जिससे null [String](../../system/string/) पर सदस्य फ़ंक्शन को कॉल करने से बचाव होता है। टेम्पलेटेड (साधारण ओवरलोड जो const [String](../../system/string/)& लेता है, उसके बजाय) ताकि मिश्रित-प्रकार कॉल्स—उदाहरण के लिए char16_t स्ट्रिंग लिटरल की तुलना [String](../../system/string/) से—एकल संगत T को डिड्यूस करने में विफल हों और इस उम्मीदवार से पूरी तरह बाहर हो जाएँ, बजाय long long/int selector पैरामीटर के माध्यम से AreEqualImpl<T1,T2> टेम्पलेट के साथ प्रतिस्पर्धा करने और अस्पष्ट ओवरलोड रिज़ॉल्यूशन उत्पन्न करने के।

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार, [System::String](../../system/string/) तक सीमित। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T& | LHS मान। |
| rhs | const T& | RHS मान। |
| s | long long | सेवा पैरामीटर जो फ़ंक्शन कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली का एसर्‍शन परिणाम।

## संबंधित देखें

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Class [Stream](../../system.io/stream/)
* Class [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)