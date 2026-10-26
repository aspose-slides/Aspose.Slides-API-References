---
title: LINQ_OrderBy()
second_title: Référence de l'API Aspose.Slides pour C++
description: Trie les éléments d'une séquence par ordre croissant en fonction des valeurs de clé sélectionnées par keySelector.
type: docs
weight: 209
url: /fr/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) méthode

Trie les éléments d’une séquence par ordre croissant selon les valeurs de clé sélectionnées par keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| keySelector | Une fonction pour extraire une clé d’un élément. |

### Valeur de retour

Un IOrderedEnumerable dont les éléments sont triés selon une clé

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) méthode

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Classe [Func](../../../system/func/)
* Classe [IEnumerable](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)