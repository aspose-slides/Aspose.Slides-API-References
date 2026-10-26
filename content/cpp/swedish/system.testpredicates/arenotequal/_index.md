---
title: AreNotEqual()
second_title: Aspose.Slides för C++ API-referens
description: Inte lika jämför argument för AreEqual påståendeöversättning.
type: docs
weight: 40
url: /sv/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) funktion

Inte lika jämför argument för AreEqual påståendeöversättning.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1\&& | LHS value. |
| rhs | T2\&& | RHS value. |

### Returvärde

gtest-stilt påståenderesultat.

## Se även

* Namnrymd [System::TestPredicates](../)
* Bibliotek [Aspose.Slides](../../)