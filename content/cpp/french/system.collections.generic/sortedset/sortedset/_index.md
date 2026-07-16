---
title: SortedSet()
second_title: Référence API Aspose.Slides pour C++
description: Crée un ensemble vide.
type: docs
weight: 1
url: /fr/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() constructeur

Crée un ensemble vide.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) constructeur

Crée un ensemble vide avec la capacité spécifiée.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) constructeur

Crée un ensemble vide qui utilise le comparateur d'égalité spécifié.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) objet à associer avec [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructeur

Crée [SortedSet](../) basé sur les valeurs énumérables.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SortedSet](../)
* Classe [IComparer](../../icomparer/)
* Classe [IEnumerable](../../ienumerable/)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)