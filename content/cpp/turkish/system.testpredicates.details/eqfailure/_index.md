---
title: EqFailure()
second_title: Aspose.Slides for C++ API Referansı
description: Çıktı için == doğrulama hatasını biçimler.
type: docs
weight: 27
url: /tr/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) fonksiyon

Çıktı için == doğrulama hatasını biçimler.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS değer tipi. |
| T2 | RHS değer tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | T1\& | LHS değeri. |
| rhs | T2\& | RHS değeri. |

### Dönüş Değeri

[Object](../../system/object/) kapsayan hata metni.

## İlgili

* Ad alanı [System::TestPredicates::Details](../)
* Kütüphane [Aspose.Slides](../../)