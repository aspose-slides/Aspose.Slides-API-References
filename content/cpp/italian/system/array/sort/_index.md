---
title: Sort()
second_title: Riferimento API di Aspose.Slides per C++
description: Ordina gli elementi nell'array specificato usando il comparatore predefinito.
type: docs
weight: 742
url: /it/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) metodo

Ordina gli elementi nell'array specificato usando il comparatore predefinito.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array di destinazione |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) metodo

Ordina un intervallo di elementi nell'array specificato usando il comparatore predefinito.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array di destinazione |
| startIndex | int | L'indice che indica l'inizio dell'intervallo di elementi da ordinare |
| count | int | La dimensione dell'intervallo di elementi da ordinare |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metodo

Ordina gli elementi nell'array specificato usando il comparatore specificato.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array di destinazione |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | Oggetto IComparer<T> utilizzato per confrontare gli elementi dell'array |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) metodo

NON IMPLEMENTATO.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) metodo

Ordina gli elementi nell'array specificato usando il confronto specificato.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) metodo

Ordina due array, uno contenente le chiavi e l'altro gli elementi corrispondenti, basandosi sui valori dell'array contenente le chiavi, i cui elementi sono confrontati usando l'operatore<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Il tipo degli elementi nell'array **keys** |
| TValue | Il tipo degli elementi nell'array **items** |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) che contiene i valori delle chiavi |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) che contiene gli elementi mappati ai valori delle chiavi nell'array **keys** |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) metodo

Ordina due array, uno contenente le chiavi e l'altro gli elementi corrispondenti, basandosi sui valori dell'array contenente le chiavi, i cui elementi sono confrontati usando il comparatore predefinito.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Il tipo degli elementi nell'array **keys** |
| TValue | Il tipo degli elementi nell'array **items** |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) che contiene i valori delle chiavi |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) che contiene gli elementi mappati ai valori delle chiavi nell'array **keys** |
| index | int | L'indice che indica l'inizio dell'intervallo da ordinare |
| length | int | Il numero di elementi nell'intervallo da ordinare |

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)