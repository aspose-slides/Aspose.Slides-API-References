---
title: SameFailure()
second_title: Referensi API Aspose.Slides untuk C++
description: Memformat kegagalan pernyataan 'same' untuk output.
type: docs
weight: 53
url: /id/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) fungsi

Memformat kegagalan pernyataan 'same' untuk output.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe nilai LHS. |
| T2 | Tipe nilai RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | T1\& | Nilai LHS. |
| rhs | T2\& | Nilai RHS. |

### Nilai Kembali

[Object](../../system/object/) membungkus teks kegagalan.

## Lihat Juga

* Ruang nama [System::TestPredicates::Details](../)
* Perpustakaan [Aspose.Slides](../../)