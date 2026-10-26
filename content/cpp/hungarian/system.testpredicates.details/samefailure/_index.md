---
title: SameFailure()
second_title: Aspose.Slides C++ API referencia
description: Formázza a 'same' állítás hibáját a kimenethez.
type: docs
weight: 53
url: /hu/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) function

Formázza a 'same' állítás hibáját a kimenethez.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS értéktípus. |
| T2 | RHS értéktípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS kifejezés. |
| rhs_expr | const char * | RHS kifejezés. |
| lhs | T1\& | LHS érték. |
| rhs | T2\& | RHS érték. |

### Visszatérési érték

[Object](../../system/object/) a hiba szövegének csomagolása.

## Lásd még

* Névtere [System::TestPredicates::Details](../)
* Könyvtár [Aspose.Slides](../../)