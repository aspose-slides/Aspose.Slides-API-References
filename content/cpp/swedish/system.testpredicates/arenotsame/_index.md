---
title: AreNotSame()
second_title: Aspose.Slides för C++ API-referens
description: Are-not-same jämför argument för AreSame påstående översättning.
type: docs
weight: 92
url: /sv/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) function

Are-not-same jämför argument för AreSame-påståendets översättning.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-objekttyp. |
| T2 | RHS-objekttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |

### Returvärde

gtest-stilat påstående-resultat.

## Se även

* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)