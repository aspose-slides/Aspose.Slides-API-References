---
title: AreEqual()
second_title: Aspose.Slides için C++ API Referansı
description: AreEqual doğrulama çevirisi için argümanları eşit karşılaştırır.
type: docs
weight: 14
url: /tr/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) fonksiyon


Equal, AreEqual doğrulama çevirisi için argümanları karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS nesne türü. |
| T2 | RHS nesne türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifade. |
| rhs_expr | const char * | RHS ifade. |
| lhs | T1\&& | LHS değer. |
| rhs | T2\&& | RHS değer. |

### Dönüş Değeri

gtest-styled doğrulama sonucu.

## Ayrıca Bakınız

* Ad alanı [System::TestPredicates](../)
* Kütüphane [Aspose.Slides](../../)