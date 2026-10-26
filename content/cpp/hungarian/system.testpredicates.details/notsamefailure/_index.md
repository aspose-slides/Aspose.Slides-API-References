---
title: NotSameFailure()
second_title: Aspose.Slides C++ API Referencia
description: Formázza a 'not same' állítási hibát a kimenethez.
type: docs
weight: 66
url: /hu/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) függvény


Formázza a 'not same' állítási hibát a kimenethez.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS érték típusa. |
| T2 | RHS érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS kifejezése. |
| rhs_expr | const char * | RHS kifejezése. |
| lhs | T1\& | LHS érték. |
| rhs | T2\& | RHS érték. |

### Visszatérési érték

[Object](../../system/object/) a hiba szövegének becsomagolása.

## Lásd még

* Névtere [System::TestPredicates::Details](../)
* Könyvtár [Aspose.Slides](../../)