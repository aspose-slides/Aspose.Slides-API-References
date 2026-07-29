---
title: NotEqFailure()
second_title: Aspose.Slides för C++ API-referens
description: Formaterar != påståendefel för utskrift.
type: docs
weight: 40
url: /sv/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) funktion

Formaterar != påståendefel för utskrift.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T1 | LHS värdetyp. |
| T2 | RHS värdetyp. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS uttryck. |
| rhs_expr | const char * | RHS uttryck. |
| lhs | T1\& | LHS värde. |
| rhs | T2\& | RHS värde. |

### Returvärde

[Object](../../system/object/) omsluter felmeddelandetext.

## Se även

* Namnrymd [System::TestPredicates::Details](../)
* Bibliotek [Aspose.Slides](../../)