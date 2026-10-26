---
title: AreNotEqual()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan argumen tidak sama untuk terjemahan pernyataan AreEqual.
type: docs
weight: 40
url: /id/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) fungsi

Tidak-sama membandingkan argumen untuk terjemahan pernyataan AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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

### Nilai Kembalian

hasil pernyataan bergaya gtest.

## Lihat Juga

* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)