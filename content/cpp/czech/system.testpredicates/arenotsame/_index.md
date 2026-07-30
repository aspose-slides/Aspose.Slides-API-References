---
title: AreNotSame()
second_title: Aspose.Slides pro C++ API Reference
description: Are-not-same porovnává argumenty pro asertaci AreSame.
type: docs
weight: 92
url: /cs/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) funkce

Are-not-same porovnává argumenty pro asertaci AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ objektu LHS. |
| T2 | Typ objektu RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const T1\& | Hodnota LHS. |
| rhs | const T2\& | Hodnota RHS. |

### Návratová hodnota

gtest-styled výsledek aserce.

## Viz také

* Jmenný prostor [System::TestPredicates](../)
* Knihovna [Aspose.Slides](../../)