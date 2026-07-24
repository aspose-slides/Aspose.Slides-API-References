---
title: AreNotSame()
second_title: Aspose.Slides için C++ API Referansı
description: Are-not-same, AreSame doğrulaması için argümanları karşılaştırır.
type: docs
weight: 92
url: /tr/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) fonksiyon


Are-not-same, AreSame doğrulaması için argümanları karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

gtest-stilinde doğrulama sonucu.

## Ayrıca Bakınız

* AdAlanı [System::TestPredicates](../)
* Kütüphane [Aspose.Slides](../../)