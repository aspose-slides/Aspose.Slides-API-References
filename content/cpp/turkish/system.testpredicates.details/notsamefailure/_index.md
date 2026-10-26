---
title: NotSameFailure()
second_title: Aspose.Slides için C++ API Referansı
description: Çıktı için 'aynı değil' doğrulama hatasını biçimlendir.
type: docs
weight: 66
url: /tr/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) fonksiyon


'not same' doğrulama hatasını çıktı için biçimlendir.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T1 | LHS değer tipi. |
| T2 | RHS değer tipi. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | T1\& | LHS değeri. |
| rhs | T2\& | RHS değeri. |

### Dönüş Değeri

[Object](../../system/object/) hata metnini sarmalar.

## Ayrıca Bakınız

* İsim uzayı [System::TestPredicates::Details](../)
* Kütüphane [Aspose.Slides](../../)