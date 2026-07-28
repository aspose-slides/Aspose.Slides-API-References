---
title: AreNotEqual()
second_title: Aspose.Slides C++ API referencia
description: A Not-equal összehasonlítja az argumentumokat az AreNotEqual állítás fordításához.
type: docs
weight: 131
url: /hu/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) függvény

Az Not-equal összehasonlítja az argumentumokat az AreNotEqual állítás fordításához.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS objektum típusa. |
| T2 | RHS objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS kifejezés. |
| rhs_expr | const char * | RHS kifejezés. |
| lhs | const T1\& | LHS érték. |
| rhs | const T2\& | RHS érték. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## Lásd még

* Névtere [System::TestPredicates::Details::SharedPtrAsserts](../)
* Könyvtár [Aspose.Slides](../../)