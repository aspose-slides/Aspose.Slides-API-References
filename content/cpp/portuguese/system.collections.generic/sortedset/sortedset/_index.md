---
title: SortedSet()
second_title: Referência da API Aspose.Slides para C++
description: Cria um conjunto vazio.
type: docs
weight: 1
url: /pt/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() constructor

Cria um conjunto vazio.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) constructor

Cria um conjunto vazio com capacidade especificada.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) constructor

Cria um conjunto vazio que usa o comparador de igualdade especificado.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) objeto a ser associado com [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructor

Cria [SortedSet](../) baseado em valores enumeráveis.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SortedSet](../)
* Classe [IComparer](../../icomparer/)
* Classe [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)