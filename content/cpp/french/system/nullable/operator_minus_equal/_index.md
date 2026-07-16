---
title: operator-=()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une instance de la classe Nullable qui représente une valeur nulle.
type: docs
weight: 248
url: /fr/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) méthode

Renvoie une instance de la classe [Nullable](../) qui représente une valeur nulle.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) méthode

Applique [operator-=()](./) à la valeur représentée par l'objet actuel en utilisant la valeur spécifiée comme argument du côté droit.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type de la valeur utilisée comme valeur du côté droit de [operator-=()](./) |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const T1\& | Une référence constante à la valeur qui est utilisée comme valeur du côté droit du [operator-=()](./) appliqué à la valeur représentée par l'objet actuel. |

### Valeur de retour

Une référence à lui-même

## Nullable::operator-=(const Nullable\<T1\>\&) méthode

Applique [operator-=()](./) à la valeur représentée par l'objet actuel en utilisant la valeur représentée par l'objet [Nullable](../) spécifié comme argument du côté droit.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type sous-jacent d'un objet [Nullable](../) dont la valeur représentée est utilisée comme argument du côté droit de [operator-=()](./) |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Une référence constante à l'objet [Nullable](../) dont la valeur représentée est utilisée comme argument du côté droit du [operator-=()](./) appliqué à la valeur représentée par l'objet actuel. |

### Valeur de retour

Une référence à lui-même

## Voir aussi

* Classe [Nullable](../)
* Structure [IsNullable](../../isnullable/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)