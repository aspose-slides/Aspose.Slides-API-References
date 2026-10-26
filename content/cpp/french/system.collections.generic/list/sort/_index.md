---
title: Sort()
second_title: Référence API Aspose.Slides pour C++
description: Trie les éléments de la liste.
type: docs
weight: 521
url: /fr/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) méthode

Trie les éléments de la liste.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Comparateur à utiliser. |

## List::Sort() méthode

Trie les éléments de la liste en utilisant le comparateur par défaut.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) méthode

Trie les éléments de la tranche de la liste.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice de début de la tranche. |
| count | int | Taille de la tranche. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Comparateur à utiliser. |

## List::Sort(Comparison\<T\>, bool) méthode

Trie les éléments de la liste.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) à utiliser. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComparer](../../icomparer/)
* Classe [List](../)
* Classe [Comparison](../../../system/comparison/)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)