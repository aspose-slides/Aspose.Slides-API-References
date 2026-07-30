---
title: AreEqual()
second_title: Riferimento API Aspose.Slides per C++
description: Confronta per uguaglianza gli argomenti per la traduzione dell'asserzione AreEqual.
type: docs
weight: 92
url: /it/system.testpredicates.details.sharedptrasserts/areequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *, const char *, const T1\&, const T2\&) funzione

Confronta per uguaglianza gli argomenti per la traduzione dell'asserzione AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo oggetto LHS. |
| T2 | Tipo oggetto RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T1\& | Valore LHS. |
| rhs | const T2\& | Valore RHS. |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## Vedi anche

* Spazio dei nomi [System::TestPredicates::Details::SharedPtrAsserts](../)
* Libreria [Aspose.Slides](../../)