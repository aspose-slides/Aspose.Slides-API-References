---
title: BinarySearch()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche un élément dans une liste triée.
type: docs
weight: 339
url: /fr/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const méthode

Recherche un élément dans une liste triée.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| item | const T\& | Élément à rechercher. |

### Valeur de retour

Indice de l'élément dans la liste triée ou complément de l'indice le plus proche.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const méthode

Recherche un élément dans une liste triée.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| item | const T\& | Élément à rechercher. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) à utiliser. |

### Valeur de retour

Indice de l'élément dans la liste triée ou complément de l'indice le plus proche.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const méthode

Recherche un élément dans une liste triée.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Début de la plage. |
| count | int | Taille de la plage. |
| item | const T\& | Élément à rechercher. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) à utiliser. |

### Valeur de retour

Indice de l'élément dans la liste triée ou complément de l'indice le plus proche.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [List](../)
* Classe [IComparer](../../icomparer/)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)