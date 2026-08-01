---
title: NotSameFailure()
second_title: Aspose.Slides voor C++ API-referentie
description: Formatteert 'not same' assertiefout voor uitvoer.
type: docs
weight: 66
url: /nl/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) functie

Formateert 'not same' assertiefout voor uitvoer.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | type van LHS-waarde. |
| T2 | type van RHS-waarde. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | T1\& | LHS-waarde. |
| rhs | T2\& | RHS-waarde. |

### Retourwaarde

[Object](../../system/object/) omhult fouttekst.

## Zie ook

* Naamruimte [System::TestPredicates::Details](../)
* Bibliotheek [Aspose.Slides](../../)