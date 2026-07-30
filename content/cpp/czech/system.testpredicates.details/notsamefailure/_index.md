---
title: NotSameFailure()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Formátuje selhání tvrzení 'not same' pro výstup.
type: docs
weight: 66
url: /cs/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) function

Formátuje selhání tvrzení 'not same' pro výstup.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS value type. |
| T2 | RHS value type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1\& | LHS value. |
| rhs | T2\& | RHS value. |

### Návratová hodnota

[Object](../../system/object/) zabaluje text selhání.

## Viz také

* Jmenný prostor [System::TestPredicates::Details](../)
* Knihovna [Aspose.Slides](../../)