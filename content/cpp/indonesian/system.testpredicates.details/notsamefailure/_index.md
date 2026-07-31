---
title: NotSameFailure()
second_title: Referensi API Aspose.Slides untuk C++
description: Memformat kegagalan asersi 'not same' untuk output.
type: docs
weight: 66
url: /id/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) fungsi

Memformat kegagalan asersi 'not same' untuk output.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | tipe nilai LHS. |
| T2 | tipe nilai RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | ekspresi LHS. |
| rhs_expr | const char * | ekspresi RHS. |
| lhs | T1\& | nilai LHS. |
| rhs | T2\& | nilai RHS. |

### Nilai Kembali

[Object](../../system/object/) membungkus teks kegagalan.

## Lihat Juga

* Ruang nama [System::TestPredicates::Details](../)
* Pustaka [Aspose.Slides](../../)