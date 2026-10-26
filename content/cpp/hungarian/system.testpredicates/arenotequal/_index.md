---
title: AreNotEqual()
second_title: Aspose.Slides C++ API referencia
description: A nem-egyenlő összehasonlítja az argumentumokat az AreEqual állítás fordítása során.
type: docs
weight: 40
url: /hu/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) függvény


A Not-equal a paramétereket hasonlítja össze az AreEqual állítás fordítása során.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS objektum típus. |
| T2 | RHS objektum típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS kifejezés. |
| rhs_expr | const char * | RHS kifejezés. |
| lhs | T1\&& | LHS érték. |
| rhs | T2\&& | RHS érték. |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## Lásd még

* Névtér [System::TestPredicates](../)
* Könyvtár [Aspose.Slides](../../)