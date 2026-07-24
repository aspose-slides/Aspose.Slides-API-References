---
title: IsInstanceOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Is-instance-of vergleicht Argumente für die IsInstanceOf-Assertion.
type: docs
weight: 118
url: /de/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) Funktion

Is-instance-of vergleicht Argumente für die IsInstanceOf-Assertion.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Argumenttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Ein typeInfo-Objekt, das einen Typ darstellt, gegen den der Typ von **obj** verglichen wird |
| obj | const T\& | Ein Objekt, dessen Typ mit dem angegebenen Typ verglichen wird |

### Rückgabewert

gtest-stilisiertes Assertionsergebnis.

## Siehe auch

* Klasse [TypeInfo](../../system/typeinfo/)
* Namensraum [System::TestPredicates](../)
* Bibliothek [Aspose.Slides](../../)