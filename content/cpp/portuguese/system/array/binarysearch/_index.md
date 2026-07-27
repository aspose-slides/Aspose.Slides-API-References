---
title: BinarySearch()
second_title: Aspose.Slides para C++ Referência da API
description: Executa busca binária no array ordenado.
type: docs
weight: 612
url: /pt/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) método

Executa busca binária no array ordenado.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Array ordenado para realizar a pesquisa |
| item | const T\& | Um item a ser procurado |

### Valor de Retorno

[Index](../../index/) do item pesquisado se encontrado, caso contrário, um inteiro negativo que é o complemento bit a bit do índice do próximo item maior que o item pesquisado ou, se não houver item maior, o complemento bit a bit do número de elementos no array.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) método

NÃO IMPLEMENTADO.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [Array](../)
* Classe [IComparer](../../../system.collections.generic/icomparer/)
* Espaço de nomes [System](../../)
* Library [Aspose.Slides](../../../)