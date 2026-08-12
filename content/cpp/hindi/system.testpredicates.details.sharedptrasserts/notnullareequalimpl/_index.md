---
title: NotNullAreEqualImpl()
second_title: Aspose.Slides for C++ API संदर्भ
description: ऐरे या सूचियों की समानता की तुलना करता है।
type: docs
weight: 40
url: /hi/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) फ़ंक्शन

ऐरे या सूचियों की समानता की तुलना करता है।

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T1 | LHS कंटेनर प्रकार। |
| T2 | RHS कंटेनर प्रकार। |

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS एक्सप्रेशन। |
| rhs_expr | const char * | RHS एक्सप्रेशन। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |
| s | long long | वह सर्विस पैरामीटर जो फ़ंक्शन के कार्यान्वयन का चयन करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली का एसेर्शन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) फ़ंक्शन

IEnumerable इंस्टेंसेस की समानता की तुलना करता है।

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T1 | LHS एलिमेंट प्रकार। |
| T2 | RHS एलिमेंट प्रकार। |

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS एक्सप्रेशन। |
| rhs_expr | const char * | RHS एक्सप्रेशन। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |
| s | long long | वह सर्विस पैरामीटर जो फ़ंक्शन के कार्यान्वयन का चयन करता है; पैरामीटर का मान अनदेखा किया जाता है। |

### वापसी मान

gtest-शैली का एसेर्शन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) फ़ंक्शन

अज्ञात प्रकारों की समानता की तुलना Equals मेथड का उपयोग करके करता है।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T1 | LHS ऑब्जेक्ट प्रकार। |
| T2 | RHS ऑब्जेक्ट प्रकार। |

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS एक्सप्रेशन। |
| rhs_expr | const char * | RHS एक्सप्रेशन। |
| lhs | const T1\& | LHS मान। |
| rhs | const T2\& | RHS मान। |

### वापसी मान

gtest-शैली का एसेर्शन परिणाम।

## देखें भी

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)