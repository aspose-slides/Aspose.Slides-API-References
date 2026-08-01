---
title: AreEqual()
second_title: Aspose.Slides voor C++ API-referentie
description: Equal vergelijkt argumenten voor de AreEqual-assertievertaling.
type: docs
weight: 14
url: /nl/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) functie

Vergelijkt argumenten voor AreEqual-assertievertaling.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS objecttype. |
| T2 | RHS objecttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | T1\&& | LHS-waarde. |
| rhs | T2\&& | RHS-waarde. |

### Retourwaarde

gtest-stijl assertieresultaat.

## Zie ook

* Naamruimte [System::TestPredicates](../)
* Bibliotheek [Aspose.Slides](../../)