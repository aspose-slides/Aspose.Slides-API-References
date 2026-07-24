---
title: AreNotSame()
second_title: Aspose.Slides für C++ API-Referenz
description: Are-not-same vergleicht Argumente für die AreSame-Assertion-Übersetzung.
type: docs
weight: 92
url: /de/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) Funktion

Are-not-same vergleicht Argumente für die AreSame-Assertion-Übersetzung.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Objekttyp. |
| T2 | RHS-Objekttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T1\& | LHS-Wert. |
| rhs | const T2\& | RHS-Wert. |

### Rückgabewert

gtest-stiltes Assertionsergebnis.

## Siehe auch

* Namensraum [System::TestPredicates](../)
* Bibliothek [Aspose.Slides](../../)