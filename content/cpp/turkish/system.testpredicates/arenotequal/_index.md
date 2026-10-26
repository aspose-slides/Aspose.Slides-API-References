---
title: AreNotEqual()
second_title: Aspose.Slides C++ için API Referansı
description: Not-equal-compares, AreEqual doğrulama çevirisi için argümanları karşılaştırır.
type: docs
weight: 40
url: /tr/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) fonksiyon


Not-equal-compares, AreEqual doğrulama çevirisi için argümanları karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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
| lhs | T1\&& | LHS değeri. |
| rhs | T2\&& | RHS değeri. |

### Dönüş Değeri

gtest-styled doğrulama sonucu.

## İlgili

* Ad alanı [System::TestPredicates](../)
* Kütüphane [Aspose.Slides](../../)