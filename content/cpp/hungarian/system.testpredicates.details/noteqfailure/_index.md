---
title: NotEqFailure()
second_title: Aspose.Slides C++ API referencia
description: Formátum a != állítás hibájához a kimeneten.
type: docs
weight: 40
url: /hu/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) függvény

Formátum a != állítás hibájához a kimeneten.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
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

[Object](../../system/object/) hibaszöveg csomagolása.

## Lásd még

* Névtér [System::TestPredicates::Details](../)
* Könyvtár [Aspose.Slides](../../)