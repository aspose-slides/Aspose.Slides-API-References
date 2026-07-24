---
title: NotNullAreEqualImpl()
second_title: Aspose.Slides for C++ API Referansı
description: Dizileri veya listeleri eşit karşılaştırır.
type: docs
weight: 40
url: /tr/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Dizileri veya listeleri eşit karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS kapsayıcı türü. |
| T2 | RHS kapsayıcı türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T1\& | LHS değeri. |
| rhs | const T2\& | RHS değeri. |
| s | long long | İşlevin uygulanmasını seçen bir hizmet parametresi; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

IEnumerable örneklerini eşit karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS öğe türü. |
| T2 | RHS öğe türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T1\& | LHS değeri. |
| rhs | const T2\& | RHS değeri. |
| s | long long | İşlevin uygulanmasını seçen bir hizmet parametresi; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) function

Bilinmeyen türleri Equals yöntemi kullanarak eşit karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS nesne türü. |
| T2 | RHS nesne türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T1\& | LHS değeri. |
| rhs | const T2\& | RHS değeri. |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## Ayrıca Bakınız

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)