---
title: LINQ_GroupBy()
second_title: Référence de l'API Aspose.Slides pour C++
description: Regroupe les éléments d'une séquence.
type: docs
weight: 287
url: /fr/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) méthode

Regroupe les éléments d'une séquence.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Key | Le type de la clé renvoyée par keyPredicate |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Une fonction pour extraire la clé de chaque élément. |

### Valeur de retour

Un [IEnumerable](../) qui contient une séquence d'objets et une clé

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) méthode

Regroupe les éléments d'une séquence.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Key | Le type de la clé renvoyée par keyPredicate |
| Element | Le type de l'élément renvoyé par elementSelector |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Une fonction pour extraire la clé de chaque élément. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Une fonction pour extraire la clé de valeur pour chaque élément. |

### Valeur de retour

Un [IEnumerable](../) qui contient une séquence d'objets et une clé

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) méthode




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) méthode




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IEnumerable](../)
* Classe [IGrouping](../../../system.linq/igrouping/)
* Classe [Func](../../../system/func/)
* Espace de noms [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)