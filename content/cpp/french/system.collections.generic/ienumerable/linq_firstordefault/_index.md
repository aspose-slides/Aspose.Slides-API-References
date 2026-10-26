---
title: LINQ_FirstOrDefault()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le premier élément d'une séquence, ou une valeur par défaut si la séquence est vide.
type: docs
weight: 66
url: /fr/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() méthode

Renvoie le premier élément d'une séquence, ou une valeur par défaut si la séquence est vide.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### Valeur de retour

Premier élément de la séquence ou valeur par défaut construite si la séquence est vide.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) méthode

Renvoie le premier élément de la séquence qui satisfait une condition ou une valeur par défaut si aucun élément ne correspond.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Une fonction pour tester chaque élément selon une condition. |

### Valeur de retour

default(T) si la source est vide ou si aucun élément ne satisfait le test spécifié par predicate ; autrement, le premier élément de la source qui satisfait le test spécifié par predicate.

## Voir aussi

* Classe [IEnumerable](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)