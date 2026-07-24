---
title: AreEqual()
second_title: Aspose.Slides für C++ API Referenz
description: Vergleicht die Argumente für die AreEqual-Assertion auf Gleichheit.
type: docs
weight: 14
url: /de/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) Funktion

Vergleicht die Argumente für die AreEqual-Assertion.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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
| lhs | T1\&& | LHS-Wert. |
| rhs | T2\&& | RHS-Wert. |

### Rückgabewert

gtest-formatiertes Assertionsergebnis.

## Siehe auch

* Namensraum [System::TestPredicates](../)
* Bibliothek [Aspose.Slides](../../)