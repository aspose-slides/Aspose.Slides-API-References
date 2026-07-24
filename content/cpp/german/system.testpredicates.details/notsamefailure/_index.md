---
title: NotSameFailure()
second_title: Aspose.Slides für C++ API-Referenz
description: Formatiert 'not same' Assertionsfehler für die Ausgabe.
type: docs
weight: 66
url: /de/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) Funktion

Formatiert den 'not same'-Assertionsfehler für die Ausgabe.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Wertetyp. |
| T2 | RHS-Wertetyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | T1\& | LHS-Wert. |
| rhs | T2\& | RHS-Wert. |

### Rückgabewert

[Object](../../system/object/) umschließt den Fehlermeldungstext.

## Siehe auch

* Namensraum [System::TestPredicates::Details](../)
* Bibliothek [Aspose.Slides](../../)