---
title: NotNullAreNotEqualImpl()
second_title: Aspose.Slides for C++ API संदर्भ
description: Not-equal-ऐरे या सूचियों की तुलना करता है।
type: docs
weight: 105
url: /hi/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Not-equal-तुलना एरे या सूचियों की।

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS कंटेनर प्रकार। |
| T2 | RHS कंटेनर प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिप्रमाणन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Not-equal-तुलना IEnumerable उदाहरणों की।

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS एलिमेंट प्रकार। |
| T2 | RHS एलिमेंट प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |
| s | long long | एक सेवा पैरामीटर जो फ़ंक्शन के कार्यान्वयन के चयनकर्ता के रूप में कार्य करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिप्रमाणन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) function

Not-equal-तुलना अज्ञात प्रकारों की Eqauals मेथड का उपयोग कर।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | LHS अभिव्यक्ति। |
| rhs_expr | const char * | RHS अभिव्यक्ति। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिप्रमाणन परिणाम।

## See Also

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)