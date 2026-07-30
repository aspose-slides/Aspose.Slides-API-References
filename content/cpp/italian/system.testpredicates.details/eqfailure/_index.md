---
title: EqFailure()
second_title: Riferimento API di Aspose.Slides per C++
description: Formatta il fallimento dell'asserzione == per l'output.
type: docs
weight: 27
url: /it/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) funzione

Formattazione del fallimento dell'asserzione == per l'output.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T1 | Tipo di valore LHS. |
| T2 | Tipo di valore RHS. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | espressione LHS. |
| rhs_expr | const char * | espressione RHS. |
| lhs | T1\& | valore LHS. |
| rhs | T2\& | valore RHS. |

### Valore restituito

[Object](../../system/object/) che avvolge il testo di errore.

## Vedi anche

* Spazio dei nomi [System::TestPredicates::Details](../)
* Libreria [Aspose.Slides](../../)