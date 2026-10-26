---
title: AreNotEqual()
second_title: Aspose.Slides pro C++ Referenční příručka API
description: Nerovnost-porovnává argumenty pro překlad tvrzení AreNotEqual.
type: docs
weight: 131
url: /cs/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) funkce

Nerovnost-porovnává argumenty pro tvrzení AreNotEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

* jmenný prostor [System::TestPredicates::Details::SharedPtrAsserts](../)
* knihovna [Aspose.Slides](../../)