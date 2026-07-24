---
title: NotEqFailure()
second_title: Aspose.Slides for C++ API Referansı
description: Çıktı için != doğrulama hatasını formatlar.
type: docs
weight: 40
url: /tr/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) fonksiyon


Çıktı için != doğrulama hatası oluşturur.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
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

[Object](../../system/object/) başarısızlık metnini sarmalar.

## Ayrıca Bakınız

* Ad Alanı [System::TestPredicates::Details](../)
* Kütüphane [Aspose.Slides](../../)