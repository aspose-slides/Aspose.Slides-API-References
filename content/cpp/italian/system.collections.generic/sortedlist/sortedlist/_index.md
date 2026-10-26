---
title: SortedList()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruisce una lista vuota.
type: docs
weight: 1
url: /it/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() costruttore

Costruisce una lista vuota.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) costruttore

Costruisce una lista vuota.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) da usare. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) costruttore

Costruttore di copia.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) da cui copiare i dati. |

## SortedList::SortedList(const map_t\&) costruttore

Costruttore di copia.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Mappa da cui copiare i dati. |

## SortedList::SortedList(int) costruttore

Costruisce una lista vuota.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| capacity | int | Numero di elementi da riservare. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Classe [SortedList](../)
* Classe [IComparer](../../icomparer/)
* Classe [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)