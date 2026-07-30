---
title: HashSet()
second_title: Riferimento API di Aspose.Slides per C++
description: Informazioni RTTI.
type: docs
weight: 1
url: /it/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() costruttore

RTTI information.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Osservazioni

Crea un insieme vuoto. 
## HashSet::HashSet(int) costruttore

Crea un insieme vuoto con capacità specificata.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) costruttore

Crea un insieme vuoto che utilizza il comparatore di uguaglianza specificato.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) oggetto da associare al hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) costruttore

Crea un hashset basato su valori enumerabili.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HashSet](../)
* Classe [IEqualityComparer](../../iequalitycomparer/)
* Classe [IEnumerable](../../ienumerable/)
* Spazio dei nomi [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)