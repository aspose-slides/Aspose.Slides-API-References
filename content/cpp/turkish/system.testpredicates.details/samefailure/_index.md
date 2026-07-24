---
title: SameFailure()
second_title: Aspose.Slides C++ API Referansı için
description: Çıktı için 'same' doğrulama hatasını biçimlendirir.
type: docs
weight: 53
url: /tr/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) fonksiyon

Çıktı için 'same' doğrulama hatasını biçimlendirir.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS değer türü. |
| T2 | RHS değer türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifade. |
| rhs_expr | const char * | RHS ifade. |
| lhs | T1\& | LHS değer. |
| rhs | T2\& | RHS değer. |

### Dönüş Değeri

[Object](../../system/object/) başarısızlık metnini sarmalayan.

## Diğerlerine Bakın

* AdAlanı [System::TestPredicates::Details](../)
* Kütüphane [Aspose.Slides](../../)