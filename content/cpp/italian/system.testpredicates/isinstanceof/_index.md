---
title: IsInstanceOf()
second_title: Aspose.Slides per il riferimento API C++
description: Is-instance-of confronta gli argomenti per la traduzione dell'asserzione IsInstanceOf.
type: docs
weight: 118
url: /it/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) funzione

Is-instance-of confronta gli argomenti per la traduzione dell'asserzione IsInstanceOf.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo dell'argomento. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Un oggetto typeInfo che rappresenta un tipo contro il quale il tipo di **obj** deve essere confrontato |
| obj | const T\& | Un oggetto il cui tipo deve essere confrontato con il tipo specificato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## Vedi anche

* Classe [TypeInfo](../../system/typeinfo/)
* Spazio dei nomi [System::TestPredicates](../)
* Libreria [Aspose.Slides](../../)