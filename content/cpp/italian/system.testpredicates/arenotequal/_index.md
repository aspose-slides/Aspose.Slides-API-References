---
title: AreNotEqual()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta per non uguaglianza gli argomenti per la traduzione dell'asserzione AreEqual.
type: docs
weight: 40
url: /it/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) funzione

Confronta per non uguaglianza gli argomenti per la traduzione dell'asserzione AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo di oggetto LHS. |
| T2 | Tipo di oggetto RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | T1\&& | Valore LHS. |
| rhs | T2\&& | Valore RHS. |

### Valore restituito

Risultato dell'asserzione in stile gtest.

## Vedi anche

* Spazio dei nomi [System::TestPredicates](../)
* Libreria [Aspose.Slides](../../)