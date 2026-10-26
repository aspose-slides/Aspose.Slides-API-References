---
title: LastIndexOf()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina l'indice dell'ultima occorrenza dell'elemento specificato in un intervallo di elementi dell'array specificato dall'indice di partenza e dal numero di elementi nell'intervallo.
type: docs
weight: 703
url: /it/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metodo

Determina l'indice dell'ultima occorrenza dell'elemento specificato in un intervallo di elementi dell'array specificato dall'indice di partenza e dal numero di elementi nell'intervallo.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ArrayType | Tipo degli elementi nell'array di destinazione |
| ValueType | tipo dell'elemento da cercare nell'array |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) per cercare l'elemento specificato in |
| value | const [ValueType](../valuetype/)\& | Indice dell'elemento di cui determinare l'indice |
| startIndex | int | [Index](../../index/) al quale la ricerca inizia |
| count | int | Numero di elementi dell'intervallo in cui cercare |

### Valore di ritorno

[Index](../../index/) dell'ultima occorrenza dell'elemento specificato se l'elemento è trovato, altrimenti -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metodo

Determina l'indice dell'ultima occorrenza dell'elemento specificato nell'array a partire dall'indice specificato.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ArrayType | Tipo degli elementi nell'array di destinazione |
| ValueType | tipo dell'elemento da cercare nell'array |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) per cercare l'elemento specificato in |
| value | const [ValueType](../valuetype/)\& | Indice dell'elemento di cui determinare l'indice |
| startIndex | int | [Index](../../index/) al quale la ricerca inizia |

### Valore di ritorno

[Index](../../index/) dell'ultima occorrenza dell'elemento specificato se l'elemento è trovato, altrimenti -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metodo

Determina l'indice dell'ultima occorrenza dell'elemento specificato nell'array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ArrayType | Tipo degli elementi nell'array di destinazione |
| ValueType | tipo dell'elemento da cercare nell'array |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) per cercare l'elemento specificato in |
| value | const [ValueType](../valuetype/)\& | Indice dell'elemento di cui determinare l'indice |

### Valore di ritorno

[Index](../../index/) dell'ultima occorrenza dell'elemento specificato se l'elemento è trovato, altrimenti -1

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Classe [Array](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)