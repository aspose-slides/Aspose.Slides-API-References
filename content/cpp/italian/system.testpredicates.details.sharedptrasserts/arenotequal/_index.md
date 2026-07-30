---
title: AreNotEqual()
second_title: Riferimento API Aspose.Slides per C++
description: Confronta gli argomenti non uguali per l'asserzione AreNotEqual.
type: docs
weight: 131
url: /it/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) function


Confronta gli argomenti non uguali per l'asserzione AreNotEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |

### Valore di ritorno

gtest-styled assertion result.

## Vedi anche

* Spazio dei nomi [System::TestPredicates::Details::SharedPtrAsserts](../)
* Libreria [Aspose.Slides](../../)