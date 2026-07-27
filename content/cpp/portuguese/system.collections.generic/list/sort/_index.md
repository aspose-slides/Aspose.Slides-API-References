---
title: Sort()
second_title: Aspose.Slides para C++ Referência da API
description: Ordena os elementos na lista.
type: docs
weight: 521
url: /pt/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) método


Ordena os elementos na lista.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Comparador a ser usado. |

## List::Sort() método


Ordena os elementos na lista usando o comparador padrão.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) método


Ordena os elementos na fatia da lista.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice inicial da fatia. |
| count | int | Tamanho da fatia. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Comparador a ser usado. |

## List::Sort(Comparison\<T\>, bool) método


Ordena os elementos na lista.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) a ser usado. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComparer](../../icomparer/)
* Classe [List](../)
* Classe [Comparison](../../../system/comparison/)
* Namespace [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)