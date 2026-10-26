---
title: NotEqFailure()
second_title: Riferimento API Aspose.Slides per C++
description: Formatta il fallimento dell'asserzione != per l'output.
type: docs
weight: 40
url: /it/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) funzione

Formatta il fallimento dell'asserzione != per l'output.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T1 | Tipo del valore LHS. |
| T2 | Tipo del valore RHS. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | T1\& | Valore LHS. |
| rhs | T2\& | Valore RHS. |

### Valore di ritorno

[Object](../../system/object/) avvolge il testo del fallimento.

## Vedi anche

* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)