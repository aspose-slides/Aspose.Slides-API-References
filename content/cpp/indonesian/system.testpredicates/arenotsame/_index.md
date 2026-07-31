---
title: AreNotSame()
second_title: Referensi API Aspose.Slides untuk C++
description: Are-not-same membandingkan argumen untuk terjemahan asersi AreSame.
type: docs
weight: 92
url: /id/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) fungsi

Are-not-same-compares membandingkan argumen untuk terjemahan asersi AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | tipe objek LHS. |
| T2 | tipe objek RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | ekspresi LHS. |
| rhs_expr | const char * | ekspresi RHS. |
| lhs | const T1\& | nilai LHS. |
| rhs | const T2\& | nilai RHS. |

### Nilai Kembali

gtest-styled assertion result.

## Lihat Juga

* Namespace [System::TestPredicates](../)
* Pustaka [Aspose.Slides](../../)