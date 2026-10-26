---
title: AreNotSame()
second_title: Aspose.Slides C++ API referencia
description: Az Are-not-same összehasonlítja az argumentumokat az AreSame állítás fordításához.
type: docs
weight: 92
url: /hu/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) függvény


Az Are-not-same összehasonlítja az argumentumokat az AreSame állítás esetén.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal oldal objektum típusa. |
| T2 | Jobb oldal objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Bal oldal kifejezés. |
| rhs_expr | const char * | Jobb oldal kifejezés. |
| lhs | const T1\& | Bal oldal érték. |
| rhs | const T2\& | Jobb oldal érték. |

### Visszatérési érték

gtest-stílusú állítás eredmény.

## Lásd még

* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)