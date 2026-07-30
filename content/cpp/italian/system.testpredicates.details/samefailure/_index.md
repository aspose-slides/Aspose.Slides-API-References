---
title: SameFailure()
second_title: Riferimento API Aspose.Slides per C++
description: Formatta il fallimento dell'asserzione 'same' per l'output.
type: docs
weight: 53
url: /it/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) function


Formatta il fallimento dell'asserzione 'same' per l'output.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo di valore LHS. |
| T2 | Tipo di valore RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | T1\& | Valore LHS. |
| rhs | T2\& | Valore RHS. |

### Valore di ritorno

[Object](../../system/object/) testo di avvolgimento del fallimento.

## Vedi anche

* Spazio dei nomi [System::TestPredicates::Details](../)
* Libreria [Aspose.Slides](../../)