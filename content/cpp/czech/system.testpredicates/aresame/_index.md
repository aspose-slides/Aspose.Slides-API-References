---
title: AreSame()
second_title: Aspose.Slides pro referenční příručku API C++
description: Are-same porovnává argumenty pro tvrzení AreSame.
type: docs
weight: 66
url: /cs/system.testpredicates/aresame/
---
## System::TestPredicates::AreSame(const char *, const char *, const T1\&, const T2\&) funkce

Are-same-porovnává argumenty pro tvrzení AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

Výsledek tvrzení ve stylu gtest.

## Viz také

* Jmenný prostor [System::TestPredicates](../)
* Knihovna [Aspose.Slides](../../)