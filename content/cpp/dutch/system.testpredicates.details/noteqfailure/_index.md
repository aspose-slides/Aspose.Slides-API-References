---
title: NotEqFailure()
second_title: Aspose.Slides voor C++ API-referentie
description: Formatteert != assertiefout voor uitvoer.
type: docs
weight: 40
url: /nl/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) functie

Formateert != assertiefout voor uitvoer.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS-waarde type. |
| T2 | RHS-waarde type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | T1\& | LHS-waarde. |
| rhs | T2\& | RHS-waarde. |

### Retourwaarde

[Object](../../system/object/) die de fouttekst omsluit.

## Zie ook

* Namespace [System::TestPredicates::Details](../)
* Bibliotheek [Aspose.Slides](../../)