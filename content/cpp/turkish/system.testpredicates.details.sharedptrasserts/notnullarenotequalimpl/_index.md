---
title: NotNullAreNotEqualImpl()
second_title: Aspose.Slides for C++ API Referansı
description: Eşit olmayan karşılaştırma dizileri veya listeleri karşılaştırır.
type: docs
weight: 105
url: /tr/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fonksiyon


Eşit olmayan karşılaştırma dizileri veya listeleri karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS konteyner tipi. |
| T2 | RHS konteyner tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T1\& | LHS değeri. |
| rhs | const T2\& | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fonksiyon


Eşit olmayan karşılaştırma IEnumerable örneklerini karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS öğe tipi. |
| T2 | RHS öğe tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T1\& | LHS değeri. |
| rhs | const T2\& | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) fonksiyon


Eşit olmayan karşılaştırma bilinmeyen tipleri Eqauals yöntemi kullanarak karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS nesne tipi. |
| T2 | RHS nesne tipi. |

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
* Yapı [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Ad Alanı [System::TestPredicates::Details::SharedPtrAsserts](../)
* Kütüphane [Aspose.Slides](../../)