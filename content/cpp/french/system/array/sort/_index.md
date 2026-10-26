---
title: Sort()
second_title: Référence de l'API Aspose.Slides pour C++
description: Trie les éléments du tableau spécifié en utilisant le comparateur par défaut.
type: docs
weight: 742
url: /fr/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) méthode


Trie les éléments du tableau spécifié en utilisant le comparateur par défaut.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Tableau ciblé |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) méthode


Trie une plage d'éléments du tableau spécifié en utilisant le comparateur par défaut.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Tableau ciblé |
| startIndex | int | L'index indiquant le début de la plage d'éléments à trier |
| count | int | La taille de la plage d'éléments à trier |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) méthode


Trie les éléments du tableau spécifié en utilisant le comparateur spécifié.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Tableau ciblé |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | Objet IComparer<T> utilisé pour comparer les éléments du tableau |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) méthode


NON IMPLEMENTÉ.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) méthode


Trie les éléments du tableau spécifié en utilisant la comparaison spécifiée.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) méthode


Trie deux tableaux, l'un contenant les clés et l'autre les éléments correspondants, en se basant sur les valeurs du tableau contenant les clés, dont les éléments sont comparés à l'aide de l'opérateur <.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Le type des éléments du tableau **keys** |
| TValue | Le type des éléments du tableau **items** |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) qui contient les valeurs des clés |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) qui contient les éléments associés aux valeurs des clés dans le tableau **keys** |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) méthode


Trie deux tableaux, l'un contenant les clés et l'autre les éléments correspondants, en se basant sur les valeurs du tableau contenant les clés, dont les éléments sont comparés à l'aide du comparateur par défaut.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Le type des éléments du tableau **keys** |
| TValue | Le type des éléments du tableau **items** |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) qui contient les valeurs des clés |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) qui contient les éléments associés aux valeurs des clés dans le tableau **keys** |
| index | int | L'index indiquant le début de la plage à trier |
| length | int | Le nombre d'éléments dans la plage à trier |

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)