---
title: Equals()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si la valeur représentée par l'objet actuel est égale à la valeur représentée par l'objet Nullable spécifié.
type: docs
weight: 131
url: /fr/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const méthode

Détermine si la valeur représentée par l'objet actuel est égale à la valeur représentée par l'objet [Nullable](../) spécifié.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type sous-jacent de l'objet [Nullable](../) avec lequel comparer |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const T1\& | Une référence constante à l'objet [Nullable](../) avec lequel comparer |

### Valeur de retour

Vrai si la valeur représentée par l'objet actuel est égale à la valeur représentée par l'objet [Nullable](../) spécifié, sinon - false

## Voir aussi

* Classe [Nullable](../)
* Structure [IsNullable](../../isnullable/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)