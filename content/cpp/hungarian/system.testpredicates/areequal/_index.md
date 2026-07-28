---
title: AreEqual()
second_title: Aspose.Slides for C++ API referenciája
description: Az argumentumokat egyenlőség szerint hasonlítja össze az AreEqual állítás átvitele során.
type: docs
weight: 14
url: /hu/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) függvény

Az argumentumokat a AreEqual állításhoz egyenlőség szerint hasonlítja össze.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS objektumtípus. |
| T2 | RHS objektumtípus. |

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

* Névterület [System::TestPredicates](../)
* Könyvtár [Aspose.Slides](../../)