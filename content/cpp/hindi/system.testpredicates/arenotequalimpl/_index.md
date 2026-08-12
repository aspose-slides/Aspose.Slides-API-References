---
title: AreNotEqualImpl()
second_title: Aspose.Slides का C++ API संदर्भ
description: Not-equal-मानों की तुलना करता है, जहाँ एक या दोनों Decimal हैं।
type: docs
weight: 53
url: /hi/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) फ़ंक्शन

Not-equal-तुलना मानों को करती है, जहाँ एक या दोनों [Decimal](../../system/decimal/) होते हैं।

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |
| s | long long | फ़ंक्शन के कार्यान्वयन को चुनने के लिए एक चयनकर्ता के रूप में कार्य करने वाला सेवा पैरामीटर; पैरामीटर का मान अनदेखा किया जाता है |

### रिटर्न वैल्यू

gtest-स्टाइल का असर्शन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) फ़ंक्शन

Not-equal-तुलना प्रदान किए गए Equals मेथड का उपयोग करके गैर-पॉइंटर प्रकारों की तुलना करती है।

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T\& | LHS मान। |
| rhs | const T\& | RHS मान। |
| s | long long | फ़ंक्शन के कार्यान्वयन को चुनने के लिए एक चयनकर्ता के रूप में कार्य करने वाला सेवा पैरामीटर; पैरामीटर का मान अनदेखा किया जाता है |

### रिटर्न वैल्यू

gtest-स्टाइल का असर्शन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) फ़ंक्शन

Not-equal-तुलना प्रदान किए गए Equals मेथड का उपयोग करके गैर-पॉइंटर प्रकारों की तुलना करती है।

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T\& | LHS मान। |
| rhs | const T\& | RHS मान। |
| s | long long | फ़ंक्शन के कार्यान्वयन को चुनने के लिए एक चयनकर्ता के रूप में कार्य करने वाला सेवा पैरामीटर; पैरामीटर का मान अनदेखा किया जाता है |

### रिटर्न वैल्यू

gtest-स्टाइल का असर्शन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) फ़ंक्शन

Not-equal-तुलना ऑपरेटर != द्वारा प्रदान किए गए गैर-पॉइंटर प्रकारों की तुलना करती है।

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T\& | LHS मान। |
| rhs | const T\& | RHS मान। |
| s | long long | फ़ंक्शन के कार्यान्वयन को चुनने के लिए एक चयनकर्ता के रूप में कार्य करने वाला सेवा पैरामीटर; पैरामीटर का मान अनदेखा किया जाता है |

### रिटर्न वैल्यू

gtest-स्टाइल का असर्शन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) फ़ंक्शन

Not-equal-तुलना बॉक्स करने योग्य [SmartPtr](../../system/smartptr/) मानों को अनबॉक्सिंग का उपयोग करके तुलना करती है।

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T | LHS मान। |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS मान। |
| s | long long | फ़ंक्शन के कार्यान्वयन को चुनने के लिए एक चयनकर्ता के रूप में कार्य करने वाला सेवा पैरामीटर; पैरामीटर का मान अनदेखा किया जाता है |

### रिटर्न वैल्यू

gtest-स्टाइल का असर्शन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) फ़ंक्शन

Not-equal-तुलना बॉक्स करने योग्य [SmartPtr](../../system/smartptr/) मानों को अनबॉक्सिंग का उपयोग करके तुलना करती है।

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS मान। |
| rhs | T | RHS मान। |
| s | long long | फ़ंक्शन के कार्यान्वयन को चुनने के लिए एक चयनकर्ता के रूप में कार्य करने वाला सेवा पैरामीटर; पैरामीटर का मान अनदेखा किया जाता है |

### रिटर्न वैल्यू

gtest-स्टाइल का असर्शन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) फ़ंक्शन

Not-equal-तुलना रैंडम प्रकार को nullptr के साथ तुलना करती है।

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T | LHS मान। |
| s | std::nullptr_t | फ़ंक्शन के कार्यान्वयन को चुनने के लिए एक चयनकर्ता के रूप में कार्य करने वाला सेवा पैरामीटर; पैरामीटर का मान अनदेखा किया जाता है |

### रिटर्न वैल्यू

gtest-स्टाइल का असर्शन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) फ़ंक्शन

Not-equal-तुलना रैंडम प्रकार को nullptr के साथ तुलना करती है।

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यचना। |
| rhs_expr | const char * | RHS अभिव्यचना। |
| rhs | std::nullptr_t | RHS मान। |
| s | T | फ़ंक्शन के कार्यान्वयन को चुनने के लिए एक चयनकर्ता के रूप में कार्य करने वाला सेवा पैरामीटर; पैरामीटर का मान अनदेखा किया जाता है |

### रिटर्न वैल्यू

gtest-स्टाइल का असर्शन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) फ़ंक्शन

Equal-तुलना पॉइंटर प्रकारों की तुलना करती है।

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS प्रकार। |
| T2 | RHS प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |
| s | long long | फ़ंक्शन के कार्यान्वयन को चुनने के लिए एक चयनकर्ता के रूप में कार्य करने वाला सेवा पैरामीटर; पैरामीटर का मान अनदेखा किया जाता है |

### रिटर्न वैल्यू

gtest-स्टाइल का असर्शन परिणाम।

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) फ़ंक्शन

Equal-तुलना gtest एल्गोरिदम का उपयोग करके रैंडम प्रकारों की तुलना करती है।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS प्रकार। |
| T2 | RHS प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | T1 | LHS मान। |
| rhs | T2 | RHS मान। |

### रिटर्न वैल्यू

gtest-स्टाइल का असर्शन परिणाम।

## See Also

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)