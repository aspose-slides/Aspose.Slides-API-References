---
title: AreEqual()
second_title: Aspose.Slides för C++ API-referens
description: Jämför argument för AreEqual-assertionen.
type: docs
weight: 14
url: /sv/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) funktion

Jämför argument för AreEqual-assertionen.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS objekttyp. |
| T2 | RHS objekttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS uttryck. |
| rhs_expr | const char * | RHS uttryck. |
| lhs | T1\&& | LHS värde. |
| rhs | T2\&& | RHS värde. |

### Returvärde

gtest-styled assertionsresultat.

## Se även

* Namnrymd [System::TestPredicates](../)
* Bibliotek [Aspose.Slides](../../)