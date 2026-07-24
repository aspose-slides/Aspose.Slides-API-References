---
title: AreNotSameImpl()
second_title: Aspose.Slides for C++ API Referansı
description: Are-not-same akıllı işaretçileri karşılaştırır.
type: docs
weight: 105
url: /tr/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) fonksiyonu


Are-not-same-compares akıllı işaretçileri karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | Bir hizmet parametresi, işlevin uygulanmasını seçen bir seçici olarak hizmet eder; parametrenin değeri yok sayılır. |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) fonksiyonu


Are-not-same-compares işaretçi olmayan değerleri karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
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

* Yapı [IsSmartPtr](../../system/issmartptr/)
* Ad Alanı [System::TestPredicates](../)
* Kütüphane [Aspose.Slides](../../)