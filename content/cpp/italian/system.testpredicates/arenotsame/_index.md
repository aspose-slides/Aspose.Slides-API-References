---
title: AreNotSame()
second_title: Riferimento API di Aspose.Slides per C++
description: Are-not-same confronta gli argomenti per la traduzione dell'asserzione AreSame.
type: docs
weight: 92
url: /it/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) funzione

Are-not-same confronta gli argomenti per la traduzione dell'asserzione AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T1 | Tipo di oggetto LHS. |
| T2 | Tipo di oggetto RHS. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T1\& | Valore LHS. |
| rhs | const T2\& | Valore RHS. |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## Vedi anche

* Namespace [System::TestPredicates](../)
* Libreria [Aspose.Slides](../../)