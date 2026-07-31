---
title: EqFailure()
second_title: Referensi API Aspose.Slides untuk C++
description: Memformat kegagalan assert == untuk output.
type: docs
weight: 27
url: /id/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) fungsi

Formats == kegagalan assertion untuk output.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
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

### Nilai Kembalian

[Object](../../system/object/) teks kegagalan yang dibungkus.

## Lihat Juga

* Ruang nama [System::TestPredicates::Details](../)
* Perpustakaan [Aspose.Slides](../../)