---
title: SortedList()
second_title: Referência da API Aspose.Slides para C++
description: Constrói lista vazia.
type: docs
weight: 1
url: /pt/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() construtor

Constrói lista vazia.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) construtor

Constrói lista vazia.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) para usar. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) construtor

Construtor de cópia.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) para copiar dados de. |

## SortedList::SortedList(const map_t\&) construtor

Construtor de cópia.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map para copiar dados de. |

## SortedList::SortedList(int) construtor

Constrói lista vazia.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| capacity | int | Número de elementos a reservar. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Classe [SortedList](../)
* Classe [IComparer](../../icomparer/)
* Classe [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)