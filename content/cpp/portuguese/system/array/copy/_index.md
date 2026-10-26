---
title: Copy()
second_title: Referência de API do Aspose.Slides para C++
description: Copia o número especificado de elementos do array de origem para o array de destino.
type: docs
weight: 729
url: /pt/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) método


Copia o número especificado de elementos do array de origem para o array de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array de origem |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array de destino |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) método


Copia o número especificado de elementos da visualização do array de origem para o array de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Visualização do array de origem |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array de destino |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) método


Copia o número especificado de elementos do array de origem para a visualização do array de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array de origem |
| dstArray | System::Details::ArrayView\<DstType\> | Visualização do array de destino |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) método


Copia o número especificado de elementos da visualização do array de origem para a visualização do array de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Visualização do array de origem |
| dstArray | System::Details::ArrayView\<DstType\> | Visualização do array de destino |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) método


Copia o número especificado de elementos do array de origem na pilha para o array de destino.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Array de origem na pilha |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array de destino |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) método


Copia o número especificado de elementos do array de origem para o array de destino na pilha.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array de origem |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Array de destino na pilha |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) método


Copia o número especificado de elementos do array de origem na pilha para o array de destino na pilha.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Array de origem na pilha |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Array de destino na pilha |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) método


Copia um número especificado de elementos do array de origem a partir do índice especificado para a posição especificada no array de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| SrcType | Tipo dos elementos no array de origem |
| DstType | Tipo dos elementos no array de destino |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array de origem |
| srcIndex | **int64_t** | [Index](../../index/) no array de origem designando o início do intervalo de itens a copiar |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array de destino |
| dstIndex | **int64_t** | [Index](../../index/) no array de destino para iniciar a inserção dos itens copiados |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) método


Copia um número especificado de elementos da visualização do array de origem a partir do índice especificado para a posição especificada no array de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| SrcType | Tipo dos elementos na visualização do array de origem |
| DstType | Tipo dos elementos no array de destino |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Visualização do array de origem |
| srcIndex | **int64_t** | [Index](../../index/) na visualização do array de origem designando o início do intervalo de itens a copiar |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array de destino |
| dstIndex | **int64_t** | [Index](../../index/) no array de destino para iniciar a inserção dos itens copiados |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) método


Copia um número especificado de elementos do array de origem a partir do índice especificado para a posição especificada na visualização do array de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| SrcType | Tipo dos elementos no array de origem |
| DstType | Tipo dos elementos na visualização do array de destino |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array de origem |
| srcIndex | **int64_t** | [Index](../../index/) no array de origem designando o início do intervalo de itens a copiar |
| dstArray | System::Details::ArrayView\<DstType\> | Visualização do array de destino |
| dstIndex | **int64_t** | [Index](../../index/) na visualização do array de destino para iniciar a inserção dos itens copiados |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) método


Copia um número especificado de elementos da visualização do array de origem a partir do índice especificado para a posição especificada na visualização do array de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| SrcType | Tipo dos elementos na visualização do array de origem |
| DstType | Tipo dos elementos na visualização do array de destino |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Visualização do array de origem |
| srcIndex | **int64_t** | [Index](../../index/) na visualização do array de origem designando o início do intervalo de itens a copiar |
| dstArray | System::Details::ArrayView\<DstType\> | Visualização do array de destino |
| dstIndex | **int64_t** | [Index](../../index/) na visualização do array de destino para iniciar a inserção dos itens copiados |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) método


Copia um número especificado de elementos do array de origem na pilha a partir do índice especificado para a posição especificada no array de destino.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| SrcType | Tipo dos elementos no array de origem na pilha |
| DstType | Tipo dos elementos no array de destino |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Array de origem na pilha |
| srcIndex | **int64_t** | [Index](../../index/) no array de origem na pilha designando o início do intervalo de itens a copiar |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array de destino |
| dstIndex | **int64_t** | [Index](../../index/) no array de destino para iniciar a inserção dos itens copiados |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) método


Copia um número especificado de elementos do array de origem a partir do índice especificado para a posição especificada no array de destino na pilha.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| SrcType | Tipo dos elementos no array de origem |
| DstType | Tipo dos elementos no array de destino na pilha |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array de origem |
| srcIndex | **int64_t** | [Index](../../index/) no array de origem designando o início do intervalo de itens a copiar |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Array de destino na pilha |
| dstIndex | **int64_t** | [Index](../../index/) no array de destino na pilha para iniciar a inserção dos itens copiados |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) método


Copia um número especificado de elementos do array de origem na pilha a partir do índice especificado para a posição especificada no array de destino na pilha.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| SrcType | Tipo dos elementos no array de origem na pilha |
| DstType | Tipo dos elementos no array de destino na pilha |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Array de origem na pilha |
| srcIndex | **int64_t** | [Index](../../index/) no array de origem na pilha designando o início do intervalo de itens a copiar |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Array de destino na pilha |
| dstIndex | **int64_t** | [Index](../../index/) no array de destino na pilha para iniciar a inserção dos itens copiados |
| count | **int64_t** | O número de elementos a copiar |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) método


Copia um número especificado de elementos da visualização do array de origem a partir do índice especificado para a posição especificada no array de destino na pilha.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| SrcType | Tipo dos elementos no array de origem na pilha |
| DstType | Tipo dos elementos no array de destino na pilha |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Visualização do array de origem |
| srcIndex | **int64_t** | [Index](../../index/) na visualização do array de origem designando o início do intervalo de itens a copiar |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Array de destino na pilha |
| dstIndex | **int64_t** | [Index](../../index/) no array de destino na pilha para iniciar a inserção dos itens copiados |
| count | **int64_t** | O número de elementos a copiar |

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)