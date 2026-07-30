---
title: operator==()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta due coppie chiave-valore usando la semantica 'equals'. Utilizza l'operatore == o il metodo EqualsTo per entrambe le chiavi e i valori, a seconda di quale sia definito.
type: docs
weight: 690
url: /it/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) funzione

Confronta due coppie chiave-valore usando la semantica “equals”. Utilizza l’operatore == o il metodo EqualsTo per entrambe le chiavi e i valori, a seconda di quale sia definito.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Tipo chiave. |
| TValue | Tipo valore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Operando LHS. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Operando RHS. |

### Valore di ritorno

Vero se entrambe le chiavi e i valori corrispondono, falso altrimenti.

## Vedi anche

* Classe [KeyValuePair](../keyvaluepair/)
* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)