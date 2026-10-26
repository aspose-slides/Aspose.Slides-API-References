---
title: LINQ_FirstOrDefault()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il primo elemento di una sequenza, o un valore predefinito se la sequenza è vuota.
type: docs
weight: 66
url: /it/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() metodo


Restituisce il primo elemento di una sequenza, o un valore predefinito se la sequenza è vuota.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### Valore restituito

Primo elemento nella sequenza o valore costruito di default se la sequenza è vuota.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) metodo


Restituisce il primo elemento della sequenza che soddisfa una condizione o un valore predefinito se non viene trovato alcun elemento.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Una funzione per verificare ogni elemento rispetto a una condizione. |

### Valore restituito

default(T) se la sorgente è vuota o se nessun elemento supera il test specificato da predicate; altrimenti, il primo elemento in source che supera il test specificato da predicate.

## Vedi anche

* Classe [IEnumerable](../)
* Spazio dei nomi [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)