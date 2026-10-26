---
title: NotSameFailure()
second_title: Aspose.Slides för C++ API-referens
description: Formaterar 'not same' assertionsfel för utskrift.
type: docs
weight: 66
url: /sv/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) funktion

Formaterar 'not same' assertionsfel för utskrift.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-värdetyp. |
| T2 | RHS-värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | T1\& | LHS-värde. |
| rhs | T2\& | RHS-värde. |

### Returvärde

[Object](../../system/object/) omsluter feltext.

## Se även

* Namnrymd [System::TestPredicates::Details](../)
* Bibliotek [Aspose.Slides](../../)