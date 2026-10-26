---
title: AreSame()
second_title: Aspose.Slides für C++ API-Referenz
description: Are-same vergleicht Argumente für die AreSame-Assertion-Übersetzung.
type: docs
weight: 66
url: /de/system.testpredicates/aresame/
---
## System::TestPredicates::AreSame(const char *, const char *, const T1\&, const T2\&) Funktion


Are-same vergleicht Argumente für die AreSame-Assertion-Übersetzung.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T1 | LHS Objekttyp. |
| T2 | RHS Objekttyp. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS Ausdruck. |
| rhs_expr | const char * | RHS Ausdruck. |
| lhs | const T1\& | LHS Wert. |
| rhs | const T2\& | RHS Wert. |

### Rückgabewert

gtest-stylisiertes Assertionsergebnis.

## Siehe auch

* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)