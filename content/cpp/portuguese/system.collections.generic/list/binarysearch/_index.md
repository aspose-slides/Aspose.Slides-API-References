---
title: BinarySearch()
second_title: Referência da API Aspose.Slides para C++
description: Procura o item em uma lista ordenada.
type: docs
weight: 339
url: /pt/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const método


Procura o item em uma lista ordenada.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | Item a ser procurado. |

### Valor de Retorno

[Index](../../../system/index/) do item na lista ordenada ou complemento do índice mais próximo.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const método


Procura o item em uma lista ordenada.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | Item a ser procurado. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) para usar. |

### Valor de Retorno

[Index](../../../system/index/) do item na lista ordenada ou complemento do índice mais próximo.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const método


Procura o item em uma lista ordenada.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) início. |
| count | int | [Range](../../../system/range/) tamanho. |
| item | const T\& | Item a ser procurado. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) para usar. |

### Valor de Retorno

[Index](../../../system/index/) do item na lista ordenada ou complemento do índice mais próximo.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../)
* Class [IComparer](../../icomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)