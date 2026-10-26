---
title: SameFailure()
second_title: Aspose.Slides für C++ API-Referenz
description: Formatiert die 'same'-Assertionsfehlerausgabe.
type: docs
weight: 53
url: /de/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) Funktion

Formatiert die 'same'-Assertionsfehlerausgabe.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
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

[Object](../../system/object/) umschließender Fehlermeldungstext.

## Siehe auch

* Namensraum [System::TestPredicates::Details](../)
* Bibliothek [Aspose.Slides](../../)