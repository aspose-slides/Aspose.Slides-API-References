---
title: HashSet()
second_title: Référence de l'API Aspose.Slides for C++
description: Informations RTTI.
type: docs
weight: 1
url: /fr/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() constructeur

Informations RTTI.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Remarques

Crée un ensemble vide. 

## HashSet::HashSet(int) constructeur

Crée un ensemble vide avec la capacité spécifiée.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) constructeur

Crée un ensemble vide qui utilise le comparateur d'égalité spécifié.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) objet à associer au hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructeur

Crée un hashset basé sur des valeurs énumérables.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HashSet](../)
* Classe [IEqualityComparer](../../iequalitycomparer/)
* Classe [IEnumerable](../../ienumerable/)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)