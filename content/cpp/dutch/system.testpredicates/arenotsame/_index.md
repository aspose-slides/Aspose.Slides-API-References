---
title: AreNotSame()
second_title: Aspose.Slides voor C++ API-referentie
description: Are-not-same vergelijkt argumenten voor de AreSame-assertievertaling.
type: docs
weight: 92
url: /nl/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) functie

Are-not-same-compares argumenten voor de AreSame-assertievertaling.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS-objecttype. |
| T2 | RHS-objecttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS-expressie. |
| rhs_expr | const char * | RHS-expressie. |
| lhs | const T1\& | LHS-waarde. |
| rhs | const T2\& | RHS-waarde. |

### Retourwaarde

gtest-gestyleerd assertieresultaat.

## Zie ook

* Naamruimte [System::TestPredicates](../)
* Bibliotheek [Aspose.Slides](../../)