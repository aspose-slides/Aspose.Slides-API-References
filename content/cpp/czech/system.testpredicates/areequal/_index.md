---
title: AreEqual()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává argumenty rovnocenně pro překlad tvrzení AreEqual.
type: docs
weight: 14
url: /cs/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) funkce

Porovnává argumenty pro překládání tvrzení AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | typ objektu LHS. |
| T2 | typ objektu RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | výraz LHS. |
| rhs_expr | const char * | výraz RHS. |
| lhs | T1\&& | hodnota LHS. |
| rhs | T2\&& | hodnota RHS. |

### Návratová hodnota

výsledek tvrzení ve stylu gtest.

## Viz také

* Jmenný prostor [System::TestPredicates](../)
* Knihovna [Aspose.Slides](../../)