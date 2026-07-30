---
title: EqualityComparerHashAdapter
second_title: Riferimento API di Aspose.Slides per C++
description: Adapter per usare IEqualityComparer per l'hashing. Usa l'oggetto comparatore, se impostato; altrimenti, utilizza il metodo hash disponibile selezionato usando la struct DictionaryHashSelector.
type: docs
weight: 677
url: /it/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

Adapter per usare [IEqualityComparer](../iequalitycomparer/) per l'hashing. Usa l'oggetto comparatore, se impostato; altrimenti, utilizza il metodo hash disponibile selezionato usando la struct [DictionaryHashSelector](../dictionaryhashselector/).

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Hashed | tipo. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Crea l'adapter senza comparatore da utilizzare. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Crea l'adapter con il comparatore fornito da utilizzare. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Calcola il valore hash. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Imposta il comparatore da utilizzare. |

## Vedi anche

* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)