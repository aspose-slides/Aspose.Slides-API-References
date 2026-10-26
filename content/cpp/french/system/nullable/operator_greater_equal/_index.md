---
title: operator>=()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie toujours false.
type: docs
weight: 183
url: /fr/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const method


Renvoie toujours false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### Valeur de retour

Toujours - false

## Nullable::operator>=(const T1\&) const method


Détermine si la valeur représentée par l'objet actuel est supérieure ou égale à la valeur représentée par l'objet spécifié en appliquant [operator>=()](./) à ces valeurs.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type sous-jacent de la valeur à comparer à la valeur représentée par l'objet actuel |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const T1\& | Une référence constante à un objet avec lequel comparer l'objet actuel |

### Valeur de retour

Vrai si la valeur représentée par l'objet actuel est supérieure ou égale à la valeur représentée par l'objet spécifié, sinon - false

## Nullable::operator>=(const Nullable\<T1\>\&) const method


Détermine si la valeur représentée par l'objet actuel est supérieure ou égale à la valeur représentée par l'objet [Nullable](../) spécifié en appliquant [operator>=()](./) à ces valeurs.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type sous-jacent de l'objet [Nullable](../) avec lequel comparer |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Une référence constante à l'objet [Nullable](../) avec lequel comparer |

### Valeur de retour

Vrai si la valeur représentée par l'objet actuel est supérieure ou égale à la valeur représentée par l'objet [Nullable](../) spécifié, sinon - false

## Voir aussi

* Classe [Nullable](../)
* Structure [IsNullable](../../isnullable/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)