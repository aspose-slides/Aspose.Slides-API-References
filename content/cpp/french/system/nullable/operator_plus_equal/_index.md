---
title: operator+=()
second_title: Référence de l'API Aspose.Slides pour C++
description: Réinitialise l'objet actuel de sorte qu'il représente une valeur nulle.
type: docs
weight: 235
url: /fr/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) méthode

Réinitialise l'objet actuel de sorte qu'il représente une valeur nulle.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### Valeur de retour

A copy of the self

## Nullable::operator+=(const T1\&) méthode

Applique [operator+=()](./) à la valeur représentée par l'objet actuel en utilisant la valeur spécifiée comme argument droit.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type de la valeur utilisé comme valeur à droite de [operator+=()](./) |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const T1\& | Une référence constante à la valeur qui est utilisée comme valeur de droite du [operator+=()](./) appliqué à la valeur représentée par l'objet actuel. |

### Valeur de retour

A reference to the self

## Nullable::operator+=(const Nullable\<T1\>\&) méthode

Applique [operator+=()](./) à la valeur représentée par l'objet actuel en utilisant la valeur représentée par l'objet [Nullable](../) spécifié comme argument droit.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type sous-jacent d'un objet [Nullable](../) dont la valeur représentée est utilisée comme argument de droite de [operator+=()](./) |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Une référence constante à l'objet [Nullable](../) dont la valeur représentée est utilisée comme argument de droite du [operator+=()](./) appliqué à la valeur représentée par l'objet actuel. |

### Valeur de retour

A reference to the self

## Voir aussi

* Classe [Nullable](../)
* Structure [IsNullable](../../isnullable/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)