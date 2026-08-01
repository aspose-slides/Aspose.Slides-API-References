---
title: AreNotEqual()
second_title: Aspose.Slides voor C++ API-referentie
description: Niet-gelijke vergelijkt argumenten voor AreEqual-assertie vertaling.
type: docs
weight: 40
url: /nl/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) functie

Niet-gelijke vergelijkt argumenten voor AreEqual-assertie vertaling.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | type van LHS-object. |
| T2 | type van RHS-object. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | T1\&& | LHS-waarde. |
| rhs | T2\&& | RHS-waarde. |

### Returnwaarde

gtest-gestyleerd assertieresultaat.

## Zie ook

* Namespace [System::TestPredicates](../)
* Bibliotheek [Aspose.Slides](../../)