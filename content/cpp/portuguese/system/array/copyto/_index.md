---
title: CopyTo()
second_title: Referência da API Aspose.Slides para C++
description: Copia todos os elementos do array atual para o array de destino especificado. Os elementos são inseridos no array de destino a partir do índice especificado pelo argumento arrayIndex.
type: docs
weight: 118
url: /pt/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) método

Copia todos os elementos do array atual para o array de destino especificado. Os elementos são inseridos no array de destino a partir do índice especificado pelo argumento arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Array de destino |
| arrayIndex | int | [Index](../../index/) no array de destino para iniciar a inserção dos itens copiados |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const método

Copia todos os elementos do array atual para o array de destino especificado. Os elementos são inseridos no array de destino a partir do índice especificado pelo argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| DstType | Tipo dos elementos no array de destino |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array de destino |
| dstIndex | **int64_t** | [Index](../../index/) no array de destino para iniciar a inserção dos itens copiados |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const método

Copia todos os elementos do array atual para a visualização do array de destino especificada. Os elementos são inseridos na visualização do array de destino a partir do índice especificado pelo argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| DstType | Tipo dos elementos na visualização do array de destino |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Visualização do array de destino |
| dstIndex | **int64_t** | [Index](../../index/) na visualização do array de destino para iniciar a inserção dos itens copiados |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const método

Copia um número especificado de elementos do array atual, a partir de posição especificada, para o array de destino especificado. Os elementos são inseridos no array de destino a partir do índice especificado pelo argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| DstType | Tipo dos elementos no array de destino |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array de destino |
| srcIndex | **int64_t** | [Index](../../index/) no array de origem para iniciar a cópia dos itens |
| dstIndex | **int64_t** | [Index](../../index/) no array de destino para iniciar a inserção dos itens copiados |
| count | **int64_t** | Número de elementos a copiar |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const método

Copia um número especificado de elementos do array atual, a partir de posição especificada, para a visualização do array de destino especificada. Os elementos são inseridos na visualização do array de destino a partir do índice especificado pelo argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| DstType | Tipo dos elementos na visualização do array de destino |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Visualização do array de destino |
| srcIndex | **int64_t** | [Index](../../index/) no array de origem para iniciar a cópia dos itens |
| dstIndex | **int64_t** | [Index](../../index/) na visualização do array de destino para iniciar a inserção dos itens copiados |
| count | **int64_t** | Número de elementos a copiar |

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Array](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)