---
title: AreNotEqual()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává argumenty nerovnosti pro asersi AreEqual.
type: docs
weight: 40
url: /cs/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1&&, T2&&) funkce

Not-equal porovnává argumenty pro aserce AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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
| lhs | T1&& | Hodnota LHS. |
| rhs | T2&& | Hodnota RHS. |

### Návratová hodnota

Výsledek tvrzení ve stylu gtest.

## Viz také

* Jmenný prostor [System::TestPredicates](../)
* Knihovna [Aspose.Slides](../../)