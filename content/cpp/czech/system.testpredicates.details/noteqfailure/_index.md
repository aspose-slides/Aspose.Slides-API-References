---
title: NotEqFailure()
second_title: Aspose.Slides pro C++ API Reference
description: Formátuje selhání tvrzení != pro výstup.
type: docs
weight: 40
url: /cs/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) funkce

Formátuje selhání tvrzení != pro výstup.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
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
| lhs | T1\& | Hodnota LHS. |
| rhs | T2\& | Hodnota RHS. |

### Návratová hodnota

[Object](../../system/object/) wrapping failure text.

## Viz také

* Jmenný prostor [System::TestPredicates::Details](../)
* Knihovna [Aspose.Slides](../../)