---
title: AreEqual()
second_title: Aspose.Slides C++ API-referencia
description: Az AreEqual állítás fordításához az argumentumokat egyenlőség-összehasonlítással vizsgálja.
type: docs
weight: 92
url: /hu/system.testpredicates.details.sharedptrasserts/areequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *, const char *, const T1&, const T2&) function

Az AreEqual állítás fordításához az argumentumokat egyenlőség-összehasonlítással vizsgálja.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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
| lhs | const T1& | LHS érték. |
| rhs | const T2& | RHS érték. |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## További információk

* Névterület [System::TestPredicates::Details::SharedPtrAsserts](../)
* Könyvtár [Aspose.Slides](../../)