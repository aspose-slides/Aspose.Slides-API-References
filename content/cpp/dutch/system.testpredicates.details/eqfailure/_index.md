---
title: EqFailure()
second_title: Aspose.Slides voor C++ API-referentie
description: Formatteert == assertiefout voor uitvoer.
type: docs
weight: 27
url: /nl/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) functie

Formatteert == assertiefout voor uitvoer.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS waarde type. |
| T2 | RHS waarde type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS expressie. |
| rhs_expr | const char * | RHS expressie. |
| lhs | T1\& | LHS waarde. |
| rhs | T2\& | RHS waarde. |

### Retourwaarde

[Object](../../system/object/) verpakkende fouttekst.

## Zie ook

* Namespace [System::TestPredicates::Details](../)
* Bibliotheek [Aspose.Slides](../../)