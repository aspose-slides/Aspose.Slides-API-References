---
title: EqFailure()
second_title: Aspose.Slides C++ API referencia
description: Formázza a == állítás hibáját a kimenethez.
type: docs
weight: 27
url: /hu/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) függvény

Formázza a == állítás hibáját a kimenethez.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Baloldali érték típusa. |
| T2 | Jobboldali érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | Baloldali kifejezés. |
| rhs_expr | const char * | Jobboldali kifejezés. |
| lhs | T1\& | Baloldali érték. |
| rhs | T2\& | Jobboldali érték. |

### Visszatérési érték

[Object](../../system/object/) a hiba szöveg csomagolásához.

## Lásd még

* Névtere [System::TestPredicates::Details](../)
* Könyvtár [Aspose.Slides](../../)