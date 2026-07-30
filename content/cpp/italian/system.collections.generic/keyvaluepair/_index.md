---
title: KeyValuePair
second_title: Riferimento API di Aspose.Slides per C++ 
description: "Coppia di chiave e valore. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire gli oggetti di questo tipo."
type: docs
weight: 378
url: /it/system.collections.generic/keyvaluepair/
---
## KeyValuePair classe


Coppia di chiave e valore. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare la classe [System::SmartPtr](../../system/smartptr/) per gestire gli oggetti di questo tipo.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Restituisce la chiave. |
| const TValue\& [get_Value](./get_value/)() const | Restituisce il valore. |
| int [GetHashCode](./gethashcode/)() const | Calcola l'hash della coppia chiave-valore XORando gli hash della chiave e del valore. |
| **bool** [IsNull](./isnull/)() const | Restituisce sempre false. |
| [KeyValuePair](./keyvaluepair/)() | Inizializzatore di coppia chiave-valore nullo. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Costruttore. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Costruttore di conversione di tipo. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Patch per le classi ereditate da IComparer<KeyValuePair<TKey, TValue>>, non confronta nulla. |
| [String](../../system/string/) [ToString](./tostring/)() const | Converte la coppia chiave-valore in stringa. |

## Vedi anche

* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)