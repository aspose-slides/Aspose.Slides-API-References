---
title: AreEqual()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan argumen secara setara untuk terjemahan asersi AreEqual.
type: docs
weight: 14
url: /id/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) function

Membandingkan argumen secara setara untuk asersi AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe objek LHS. |
| T2 | Tipe objek RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | T1\&& | Nilai LHS. |
| rhs | T2\&& | Nilai RHS. |

### Nilai kembali

hasil asersi bergaya gtest.

## Lihat Juga

* Ruang nama [System::TestPredicates](../)
* Pustaka [Aspose.Slides](../../)