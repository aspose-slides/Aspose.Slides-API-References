---
title: operator<()
second_title: Riferimento API di Aspose.Slides per C++
description: Patch per le classi ereditate da IComparer<KeyValuePair<TKey, TValue>>, non confronta nulla.
type: docs
weight: 53
url: /it/system.collections.generic/keyvaluepair/operator_less/
---
## KeyValuePair::operator<(const KeyValuePair\&) const metodo

Patch per le classi ereditate da IComparer<KeyValuePair<TKey, TValue>>, non confronta nulla.

```cpp
bool System::Collections::Generic::KeyValuePair<TKey, TValue>::operator<(const KeyValuePair &kvp) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| kvp | const [KeyValuePair](../)\& | Argomento fittizio. |

### Valore di ritorno

Restituisce sempre false.

## Vedi anche

* Classe [KeyValuePair](../)
* Spazio dei nomi [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)