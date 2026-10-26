---
title: EqFailure()
second_title: Aspose.Slides pro C++ – reference API
description: Formátuje selhání aserce == pro výstup.
type: docs
weight: 27
url: /cs/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) funkce

Formátuje selhání aserce == pro výstup.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ hodnoty LHS. |
| T2 | Typ hodnoty RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | T1\& | LHS hodnota. |
| rhs | T2\& | RHS hodnota. |

### Návratová hodnota

[Object](../../system/object/) zabalující text selhání.

## Viz také

* Jmenný prostor [System::TestPredicates::Details](../)
* Knihovna [Aspose.Slides](../../)