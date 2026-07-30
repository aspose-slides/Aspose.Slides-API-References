---
title: Clear()
second_title: Riferimento API di Aspose.Slides per C++
description: Non supportato perché l'array rappresentato dall'oggetto corrente è di sola lettura.
type: docs
weight: 53
url: /it/system/array/clear/
---
## Array::Clear() metodo

Non supportato perché l'array rappresentato dall'oggetto corrente è di sola lettura.

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) metodo

Sostituisce i valori **count** a partire dall'indice **startIndex** nell'array specificato con i valori predefiniti.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Type | Tipo di elementi nell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array di destinazione |
| startIndex | int | [Index](../../index/) al quale iniziare la sostituzione degli elementi |
| count | int | Il numero di elementi da sostituire |

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Metodo [Type](../../object/type/)
* Classe [Array](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)