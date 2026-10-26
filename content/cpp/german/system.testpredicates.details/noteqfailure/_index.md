---
title: NotEqFailure()
second_title: Aspose.Slides für C++ API-Referenz
description: Formatiert != Assertion-Fehler für die Ausgabe.
type: docs
weight: 40
url: /de/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) Funktion

Formatiert != Assertion-Fehler für die Ausgabe.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Werttyp. |
| T2 | RHS-Werttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | T1\& | LHS-Wert. |
| rhs | T2\& | RHS-Wert. |

### Rückgabewert

[Object](../../system/object/) umfasst Fehlermeldungstext.

## Siehe auch

* Namensraum [System::TestPredicates::Details](../)
* Bibliothek [Aspose.Slides](../../)