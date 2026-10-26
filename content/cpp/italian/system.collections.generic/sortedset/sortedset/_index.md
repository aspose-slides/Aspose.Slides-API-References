---
title: SortedSet()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un insieme vuoto.
type: docs
weight: 1
url: /it/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() costruttore

Crea un insieme vuoto.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) costruttore

Crea un insieme vuoto con la capacità specificata.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) costruttore

Crea un insieme vuoto che utilizza il comparatore di uguaglianza specificato.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) oggetto da associare a [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) costruttore

Crea [SortedSet](../) basato su valori enumerabili.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SortedSet](../)
* Classe [IComparer](../../icomparer/)
* Classe [IEnumerable](../../ienumerable/)
* Spazio dei nomi [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)