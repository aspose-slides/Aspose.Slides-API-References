---
title: LINQ_Any()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si une séquence contient des éléments.
type: docs
weight: 157
url: /fr/system.collections.generic/ienumerable/linq_any/
---
## IEnumerable::LINQ_Any() méthode

Détermine si une séquence contient des éléments.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any()
```

### Valeur de retour

true si la séquence source contient des éléments ; sinon, false.

## IEnumerable::LINQ_Any(std::function\<bool(T)>) méthode

Détermine si un élément d'une séquence existe ou satisfait une condition.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any(std::function<bool(T)> predicate)
```

### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Une fonction pour tester chaque élément selon une condition. |

### Valeur de retour

true si la séquence source contient des éléments ; sinon, false.

## Voir aussi

* Classe [IEnumerable](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)