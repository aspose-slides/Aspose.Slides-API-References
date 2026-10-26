---
title: BinarySearch()
second_title: Riferimento API di Aspose.Slides per C++
description: Cerca l'elemento in una lista ordinata.
type: docs
weight: 339
url: /it/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const metodo

Cerca l'elemento in una lista ordinata.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | const T\& | Elemento da cercare. |

### Valore restituito

[Index](../../../system/index/) dell'elemento nella lista ordinata o complemento dell'indice più vicino.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const metodo

Cerca l'elemento in una lista ordinata.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | const T\& | Elemento da cercare. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) da usare. |

### Valore restituito

[Index](../../../system/index/) dell'elemento nella lista ordinata o complemento dell'indice più vicino.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const metodo

Cerca l'elemento in una lista ordinata.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) di inizio. |
| count | int | [Range](../../../system/range/) dimensione. |
| item | const T\& | Elemento da cercare. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) da usare. |

### Valore restituito

[Index](../../../system/index/) dell'elemento nella lista ordinata o complemento dell'indice più vicino.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [List](../)
* Classe [IComparer](../../icomparer/)
* Namespace [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)