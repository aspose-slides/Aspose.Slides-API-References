---
title: AreEqual()
second_title: Aspose.Slides per C++ Riferimento API
description: Confronta per uguaglianza gli argomenti per la traduzione dell'asserzione AreEqual.
type: docs
weight: 14
url: /it/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) function

Confronta per uguaglianza gli argomenti per l'asserzione AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Parametri del template

| Parameter | Description |
| --- | --- |
| T1 | Tipo oggetto LHS. |
| T2 | Tipo oggetto RHS. |

### Argomenti

| Parameter | Type | Description |
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