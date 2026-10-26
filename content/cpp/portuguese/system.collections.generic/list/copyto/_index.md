---
title: CopyTo()
second_title: Referência da API Aspose.Slides para C++
description: Copia os elementos da lista para os elementos existentes do array.
type: docs
weight: 209
url: /pt/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) método

Copia os elementos da lista para os elementos existentes do array.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Array de destino. |
| arrayIndex | int | Índice inicial do array de destino. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) método

Copia todos os elementos para os elementos existentes do array.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) para copiar elementos. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) método

Copia elementos a partir do índice especificado para os elementos existentes do array.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Um índice baseado em zero do elemento da lista representado pelo objeto atual a partir do qual iniciar a cópia. |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) para copiar elementos. |
| arrayIndex | int | Posição inicial no array de destino. |
| count | int | Número de elementos a copiar. |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)