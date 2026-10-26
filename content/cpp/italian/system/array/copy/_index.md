---
title: Copy()
second_title: Riferimento API di Aspose.Slides per C++
description: Copia il numero specificato di elementi dall'array di origine all'array di destinazione.
type: docs
weight: 729
url: /it/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) metodo

Copia il numero specificato di elementi dall'array di origine all'array di destinazione.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array di origine |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array di destinazione |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) metodo

Copia il numero specificato di elementi dalla vista dell'array di origine all'array di destinazione.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista dell'array di origine |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array di destinazione |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) metodo

Copia il numero specificato di elementi dall'array di origine alla vista dell'array di destinazione.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array di origine |
| dstArray | System::Details::ArrayView\<DstType\> | Vista dell'array di destinazione |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) metodo

Copia il numero specificato di elementi dalla vista dell'array di origine alla vista dell'array di destinazione.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista dell'array di origine |
| dstArray | System::Details::ArrayView\<DstType\> | Vista dell'array di destinazione |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) metodo

Copia il numero specificato di elementi dall'array di origine sullo stack all'array di destinazione.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Array di origine sullo stack |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array di destinazione |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) metodo

Copia il numero specificato di elementi dall'array di origine all'array di destinazione sullo stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array di origine |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Array di destinazione sullo stack |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) metodo

Copia il numero specificato di elementi dall'array di origine sullo stack all'array di destinazione sullo stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Array di origine sullo stack |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Array di destinazione sullo stack |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metodo

Copia un numero specificato di elementi dall'array di origine a partire dall'indice specificato alla posizione specificata nell'array di destinazione.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| SrcType | Tipo degli elementi nell'array di origine |
| DstType | Tipo degli elementi nell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array di origine |
| srcIndex | **int64_t** | [Index](../../index/) nell'array di origine che indica l'inizio dell'intervallo di elementi da copiare |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array di destinazione |
| dstIndex | **int64_t** | [Index](../../index/) nell'array di destinazione dove iniziare l'inserimento degli elementi copiati |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metodo

Copia un numero specificato di elementi dalla vista dell'array di origine a partire dall'indice specificato alla posizione specificata nell'array di destinazione.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| SrcType | Tipo degli elementi nella vista dell'array di origine |
| DstType | Tipo degli elementi nell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista dell'array di origine |
| srcIndex | **int64_t** | [Index](../../index/) nella vista dell'array di origine che indica l'inizio dell'intervallo di elementi da copiare |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array di destinazione |
| dstIndex | **int64_t** | [Index](../../index/) nell'array di destinazione dove iniziare l'inserimento degli elementi copiati |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) metodo

Copia un numero specificato di elementi dall'array di origine a partire dall'indice specificato alla posizione specificata nella vista dell'array di destinazione.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| SrcType | Tipo degli elementi nell'array di origine |
| DstType | Tipo degli elementi nella vista dell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array di origine |
| srcIndex | **int64_t** | [Index](../../index/) nell'array di origine che indica l'inizio dell'intervallo di elementi da copiare |
| dstArray | System::Details::ArrayView\<DstType\> | Vista dell'array di destinazione |
| dstIndex | **int64_t** | [Index](../../index/) nella vista dell'array di destinazione dove iniziare l'inserimento degli elementi copiati |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) metodo

Copia un numero specificato di elementi dalla vista dell'array di origine a partire dall'indice specificato alla posizione specificata nella vista dell'array di destinazione.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| SrcType | Tipo degli elementi nella vista dell'array di origine |
| DstType | Tipo degli elementi nella vista dell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista dell'array di origine |
| srcIndex | **int64_t** | [Index](../../index/) nella vista dell'array di origine che indica l'inizio dell'intervallo di elementi da copiare |
| dstArray | System::Details::ArrayView\<DstType\> | Vista dell'array di destinazione |
| dstIndex | **int64_t** | [Index](../../index/) nella vista dell'array di destinazione dove iniziare l'inserimento degli elementi copiati |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metodo

Copia un numero specificato di elementi dall'array di origine sullo stack a partire dall'indice specificato alla posizione specificata nell'array di destinazione.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| SrcType | Tipo degli elementi nell'array di origine sullo stack |
| DstType | Tipo degli elementi nell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Array di origine sullo stack |
| srcIndex | **int64_t** | [Index](../../index/) nell'array di origine sullo stack che indica l'inizio dell'intervallo di elementi da copiare |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array di destinazione |
| dstIndex | **int64_t** | [Index](../../index/) nell'array di destinazione dove iniziare l'inserimento degli elementi copiati |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) metodo

Copia un numero specificato di elementi dall'array di origine a partire dall'indice specificato alla posizione specificata nell'array di destinazione sullo stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| SrcType | Tipo degli elementi nell'array di origine |
| DstType | Tipo degli elementi nell'array di destinazione sullo stack |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array di origine |
| srcIndex | **int64_t** | [Index](../../index/) nell'array di origine che indica l'inizio dell'intervallo di elementi da copiare |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Array di destinazione sullo stack |
| dstIndex | **int64_t** | [Index](../../index/) nell'array di destinazione sullo stack dove iniziare l'inserimento degli elementi copiati |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) metodo

Copia un numero specificato di elementi dall'array di origine sullo stack a partire dall'indice specificato alla posizione specificata nell'array di destinazione sullo stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| SrcType | Tipo degli elementi nell'array di origine sullo stack |
| DstType | Tipo degli elementi nell'array di destinazione sullo stack |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Array di origine sullo stack |
| srcIndex | **int64_t** | [Index](../../index/) nell'array di origine sullo stack che indica l'inizio dell'intervallo di elementi da copiare |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Array di destinazione sullo stack |
| dstIndex | **int64_t** | [Index](../../index/) nell'array di destinazione sullo stack dove iniziare l'inserimento degli elementi copiati |
| count | **int64_t** | Il numero di elementi da copiare |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) metodo

Copia un numero specificato di elementi dalla vista dell'array di origine a partire dall'indice specificato alla posizione specificata nell'array di destinazione sullo stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| SrcType | Tipo degli elementi nella vista dell'array di origine sullo stack |
| DstType | Tipo degli elementi nell'array di destinazione sullo stack |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Vista dell'array di origine |
| srcIndex | **int64_t** | [Index](../../index/) nella vista dell'array di origine che indica l'inizio dell'intervallo di elementi da copiare |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Array di destinazione sullo stack |
| dstIndex | **int64_t** | [Index](../../index/) nell'array di destinazione sullo stack dove iniziare l'inserimento degli elementi copiati |
| count | **int64_t** | Il numero di elementi da copiare |

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)