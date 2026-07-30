---
title: Sort()
second_title: Riferimento API di Aspose.Slides per C++
description: Ordina gli elementi nella lista.
type: docs
weight: 521
url: /it/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metodo

Ordina gli elementi nella lista.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Comparator da utilizzare. |

## List::Sort() metodo

Ordina gli elementi nella lista utilizzando il comparatore predefinito.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) metodo

Ordina gli elementi nella sezione della lista.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di inizio della sezione. |
| count | int | Dimensione della sezione. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Comparator da utilizzare. |

## List::Sort(Comparison\<T\>, bool) metodo

Ordina gli elementi nella lista.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) da utilizzare. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComparer](../../icomparer/)
* Classe [List](../)
* Classe [Comparison](../../../system/comparison/)
* Namespace [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)