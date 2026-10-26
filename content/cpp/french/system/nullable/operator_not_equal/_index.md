---
title: operator!=()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si la valeur représentée par l'objet actuel n'est pas nulle.
type: docs
weight: 144
url: /fr/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const méthode


Détermine si la valeur représentée par l'objet actuel n'est pas nulle, sinon - false

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### Valeur de retour

Vrai si la valeur représentée par l'objet actuel n'est pas nulle, sinon - false

## Nullable::operator!=(const T1\&) const méthode


Détermine si la valeur représentée par l'objet actuel n'est pas égale à la valeur spécifiée, sinon - false

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type de la valeur à comparer |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const T1\& | Une référence constante à la valeur à comparer |

### Valeur de retour

Vrai si la valeur représentée par l'objet actuel n'est pas égale à la valeur spécifiée, sinon - false

## Nullable::operator!=(const Nullable\<T1\>\&) const méthode


Détermine si la valeur représentée par l'objet actuel n'est pas égale à la valeur représentée par l'objet [Nullable](../) spécifié, sinon - false

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type sous-jacent de l'objet [Nullable](../) à comparer |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Une référence constante à l'objet [Nullable](../) à comparer |

### Valeur de retour

Vrai si la valeur représentée par l'objet actuel n'est pas égale à la valeur représentée par l'objet [Nullable](../) spécifié, sinon - false

## Voir aussi

* Classe [Nullable](../)
* Structure [IsNullable](../../isnullable/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)