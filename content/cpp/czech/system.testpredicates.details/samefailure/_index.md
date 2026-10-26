---
title: SameFailure()
second_title: Aspose.Slides pro referenční příručku API C++
description: Formátuje selhání tvrzení 'same' pro výstup.
type: docs
weight: 53
url: /cs/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1&, T2&) funkce

Formátuje selhání tvrzení „same“ pro výstup.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ hodnoty LHS. |
| T2 | Typ hodnoty RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | T1& | Hodnota LHS. |
| rhs | T2& | Hodnota RHS. |

### Návratová hodnota

[Object](../../system/object/) obalující text selhání.

## Viz také

* jmenný prostor [System::TestPredicates::Details](../)
* knihovna [Aspose.Slides](../../)