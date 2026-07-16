---
title: LINQ_OrderByDescending()
second_title: Référence de l'API Aspose.Slides pour C++
description: Trie les éléments d'une séquence par ordre décroissant selon les valeurs de clé sélectionnées par keySelector.
type: docs
weight: 222
url: /fr/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) méthode

Trie les éléments d'une séquence par ordre décroissant selon les valeurs de clé sélectionnées par keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| keySelector | Une fonction qui extrait une clé d'un élément. |

### Valeur de retour

Un IOrderedEnumerable dont les éléments sont triés par ordre décroissant de la clé

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) méthode

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Classe [Func](../../../system/func/)
* Classe [IEnumerable](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)