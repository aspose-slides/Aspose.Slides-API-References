---
title: AreSame()
second_title: Aspose.Slides C++ API-referencia
description: Az Are-same összehasonlítja az argumentumokat az AreSame állítás lefordításához.
type: docs
weight: 66
url: /hu/system.testpredicates/aresame/
---
## System::TestPredicates::AreSame(const char *, const char *, const T1\&, const T2\&) függvény


Az Are-same összehasonlítja az argumentumokat az AreSame állítás lefordításához.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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
| lhs | const T1\& | LHS érték. |
| rhs | const T2\& | RHS érték. |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## Lásd még

* Névtér [System::TestPredicates](../)
* Könyvtár [Aspose.Slides](../../)