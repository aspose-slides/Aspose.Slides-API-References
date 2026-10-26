---
title: EqFailure()
second_title: Aspose.Slides für C++ API-Referenz
description: Formatiert == Assertion-Fehler für die Ausgabe.
type: docs
weight: 27
url: /de/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) Funktion


Formatiert == Assertion-Fehler für die Ausgabe.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS value type. |
| T2 | RHS value type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1\& | LHS value. |
| rhs | T2\& | RHS value. |

### Rückgabewert

[Object](../../system/object/) wrapping failure text.

## Siehe auch

* Namensraum [System::TestPredicates::Details](../)
* Bibliothek [Aspose.Slides](../../)