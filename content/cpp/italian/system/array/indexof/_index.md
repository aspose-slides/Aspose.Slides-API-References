---
title: IndexOf()
second_title: Riferimento API Aspose.Slides per C++
description: Determina l'indice della prima occorrenza dell'elemento specificato nell'array.
type: docs
weight: 131
url: /it/system/array/indexof/
---
## Array::IndexOf(const T\&) const metodo


Determina l'indice della prima occorrenza dell'elemento specificato nell'array.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | const T\& | Indice dell'elemento di cui determinare |

### Valore di ritorno

[Index](../../index/) della prima occorrenza dell'elemento specificato se l'elemento è trovato, altrimenti -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metodo


Determina l'indice della prima occorrenza dell'elemento specificato nell'array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| ArrayType | Tipo degli elementi nell'array di destinazione |
| ValueType | tipo dell'elemento da cercare nell'array |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) per cercare l'elemento specificato in |
| value | const [ValueType](../valuetype/)\& | Indice dell'elemento di cui determinare |

### Valore di ritorno

[Index](../../index/) della prima occorrenza dell'elemento specificato se l'elemento è trovato, altrimenti -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metodo


Determina l'indice della prima occorrenza dell'elemento specificato nell'array iniziando dall'indice specificato.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| ArrayType | Tipo degli elementi nell'array di destinazione |
| ValueType | tipo dell'elemento da cercare nell'array |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) per cercare l'elemento specificato in |
| value | const [ValueType](../valuetype/)\& | Indice dell'elemento di cui determinare |
| startIndex | int | [Index](../../index/) al quale la ricerca inizia |

### Valore di ritorno

[Index](../../index/) della prima occorrenza dell'elemento specificato se l'elemento è trovato, altrimenti -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metodo


Determina l'indice della prima occorrenza dell'elemento specificato in un intervallo di elementi dell'array definito dall'indice di partenza e dal numero di elementi nell'intervallo.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| ArrayType | Tipo degli elementi nell'array di destinazione |
| ValueType | tipo dell'elemento da cercare nell'array |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) per cercare l'elemento specificato in |
| value | const [ValueType](../valuetype/)\& | Indice dell'elemento di cui determinare |
| startIndex | int | [Index](../../index/) al quale la ricerca inizia |
| count | int | Numero di elementi dell'intervallo in cui cercare |

### Valore di ritorno

[Index](../../index/) della prima occorrenza dell'elemento specificato se l'elemento è trovato, altrimenti -1

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)