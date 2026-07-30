---
title: AreSame()
second_title: Riferimento API Aspose.Slides per C++
description: Are-same confronta gli argomenti per l'asserzione AreSame.
type: docs
weight: 66
url: /it/system.testpredicates/aresame/
---
## System::TestPredicates::AreSame(const char *, const char *, const T1&, const T2&) funzione

Are-same confronta gli argomenti per l'asserzione AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | tipo dell'oggetto LHS. |
| T2 | tipo dell'oggetto RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | espressione LHS. |
| rhs_expr | const char * | espressione RHS. |
| lhs | const T1\& | valore LHS. |
| rhs | const T2\& | valore RHS. |

### Valore di ritorno

risultato dell'asserzione in stile gtest.

## Vedi anche

* Namespace [System::TestPredicates](../)
* Libreria [Aspose.Slides](../../)