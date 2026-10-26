---
title: SameFailure()
second_title: Aspose.Slides voor C++ API Referentie
description: Formatteert 'same' assertiefout voor uitvoer.
type: docs
weight: 53
url: /nl/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) functie

Formateert een 'same' assertiefout voor uitvoer.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Templateparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Type van LHS-waarde. |
| T2 | Type van RHS-waarde. |

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

* Naamruimte [System::TestPredicates::Details](../)
* Bibliotheek [Aspose.Slides](../../)