---
title: IsInstanceOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Is-instance-of-membandingkan argumen untuk terjemahan asersi IsInstanceOf.
type: docs
weight: 118
url: /id/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) fungsi

Is-instance-of-membandingkan argumen untuk terjemahan asersi IsInstanceOf.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe argumen. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Objek typeInfo yang mewakili tipe yang dibandingkan dengan tipe **obj**. |
| obj | const T\& | Sebuah objek yang tipenya dibandingkan dengan tipe yang ditentukan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## Lihat Juga

* Kelas [TypeInfo](../../system/typeinfo/)
* Namespace [System::TestPredicates](../)
* Perpustakaan [Aspose.Slides](../../)