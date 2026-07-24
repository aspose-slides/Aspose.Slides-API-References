---
title: AreNotEqual()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht Argumente für die AreEqual-Assertion nicht gleich.
type: docs
weight: 40
url: /de/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) Funktion

Vergleicht Argumente für die AreEqual-Assertion nicht gleich.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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

gtest-stilisiertes Assertion-Ergebnis.

## Siehe auch

* Namensraum [System::TestPredicates](../)
* Bibliothek [Aspose.Slides](../../)