---
title: WeakPtrFromTypeParameter
second_title: Référence de l'API Aspose.Slides pour C++
description: Structure de trait pour convertir le type d'argument en pointeur faible, si c'est un type pointeur.
type: docs
weight: 1990
url: /fr/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct


Structure de trait pour convertir le type d'argument en pointeur faible, si c'est un type pointeur.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)