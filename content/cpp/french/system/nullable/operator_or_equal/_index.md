---
title: operator|=()
second_title: Référence API Aspose.Slides pour C++
description: Applique operator|=() à la valeur représentée par l'objet actuel en utilisant la valeur spécifiée comme argument à droite.
type: docs
weight: 261
url: /fr/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) méthode

Applique [operator|=()](./) à la valeur représentée par l'objet actuel en utilisant la valeur spécifiée comme argument à droite.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le paramètre de modèle pour faire fonctionner SFINAE. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | **bool** | Une valeur booléenne utilisée comme valeur à droite du [operator|=()](./) appliqué à la valeur représentée par l'objet actuel. |

### Valeur de retour

Une référence à l'objet lui-même.

## Voir aussi

* Classe [Nullable](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)