---
title: CopyTo()
second_title: Riferimento API di Aspose.Slides per C++
description: Copia tutti gli elementi dell'array corrente nell'array di destinazione specificato. Gli elementi vengono inseriti nell'array di destinazione a partire dall'indice specificato dall'argomento arrayIndex.
type: docs
weight: 118
url: /it/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) metodo


Copia tutti gli elementi dell'array corrente nell'array di destinazione specificato. Gli elementi vengono inseriti nell'array di destinazione a partire dall'indice specificato dall'argomento arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Array di destinazione |
| arrayIndex | int | [Index](../../index/) nell'array di destinazione per iniziare a inserire gli elementi copiati |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const metodo


Copia tutti gli elementi dell'array corrente nell'array di destinazione specificato. Gli elementi vengono inseriti nell'array di destinazione a partire dall'indice specificato dall'argomento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| DstType | Tipo degli elementi nell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array di destinazione |
| dstIndex | **int64_t** | [Index](../../index/) nell'array di destinazione per iniziare a inserire gli elementi copiati |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const metodo


Copia tutti gli elementi dell'array corrente nella visualizzazione dell'array di destinazione specificata. Gli elementi vengono inseriti nella visualizzazione dell'array di destinazione a partire dall'indice specificato dall'argomento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| DstType | Tipo degli elementi nella visualizzazione dell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Visualizzazione dell'array di destinazione |
| dstIndex | **int64_t** | [Index](../../index/) nella visualizzazione dell'array di destinazione per iniziare a inserire gli elementi copiati |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const metodo


Copia un numero specificato di elementi dall'array corrente a partire da una posizione specificata nell'array di destinazione specificato. Gli elementi vengono inseriti nell'array di destinazione a partire dall'indice specificato dall'argomento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| DstType | Tipo degli elementi nell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array di destinazione |
| srcIndex | **int64_t** | [Index](../../index/) nell'array di origine per iniziare a copiare gli elementi |
| dstIndex | **int64_t** | [Index](../../index/) nell'array di destinazione per iniziare a inserire gli elementi copiati |
| count | **int64_t** | Numero di elementi da copiare |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const metodo


Copia un numero specificato di elementi dall'array corrente a partire da una posizione specificata nella visualizzazione dell'array di destinazione specificata. Gli elementi vengono inseriti nella visualizzazione dell'array di destinazione a partire dall'indice specificato dall'argomento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| DstType | Tipo degli elementi nella visualizzazione dell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Visualizzazione dell'array di destinazione |
| srcIndex | **int64_t** | [Index](../../index/) nella visualizzazione dell'array di origine per iniziare a copiare gli elementi |
| dstIndex | **int64_t** | [Index](../../index/) nella visualizzazione dell'array di destinazione per iniziare a inserire gli elementi copiati |
| count | **int64_t** | Numero di elementi da copiare |

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Array](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)