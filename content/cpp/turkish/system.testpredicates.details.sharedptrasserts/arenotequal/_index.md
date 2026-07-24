---
title: AreNotEqual()
second_title: Aspose.Slides for C++ API Referansı
description: AreNotEqual doğrulaması için argümanlar eşit-değil karşılaştırması yapılır.
type: docs
weight: 131
url: /tr/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) function

AreNotEqual doğrulaması için argümanlar eşit-değil karşılaştırması yapılır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sol taraf (LHS) nesne türü. |
| T2 | Sağ taraf (RHS) nesne türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf (LHS) ifadesi. |
| rhs_expr | const char * | Sağ taraf (RHS) ifadesi. |
| lhs | const T1\& | Sol taraf (LHS) değeri. |
| rhs | const T2\& | Sağ taraf (RHS) değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## Ayrıca Bakınız

* Ad alanı [System::TestPredicates::Details::SharedPtrAsserts](../)
* Kütüphane [Aspose.Slides](../../)