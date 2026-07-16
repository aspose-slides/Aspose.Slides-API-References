---
title: operator<()
second_title: Référence de l'API Aspose.Slides for C++
description: Retourne toujours false.
type: docs
weight: 170
url: /fr/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const méthode

Retourne toujours false.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const méthode

Détermine si la valeur représentée par l'objet actuel est inférieure à la valeur spécifiée en appliquant [operator<()](./) à ces valeurs.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T1 | Le type de la valeur à comparer avec |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Une référence constante à la valeur à comparer avec |

### Valeur de retour

Vrai si la valeur représentée par l'objet actuel est inférieure à la valeur spécifiée, sinon - false

## Nullable::operator<(const Nullable\<T1\>\&) const méthode

Détermine si la valeur représentée par l'objet actuel est inférieure à la valeur représentée par l'objet [Nullable](../) spécifié en appliquant [operator<()](./) à ces valeurs.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T1 | Le type sous-jacent de l'objet [Nullable](../) à comparer avec |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Une référence constante à l'objet [Nullable](../) à comparer avec |

### Valeur de retour

Vrai si la valeur représentée par l'objet actuel est inférieure à la valeur représentée par l'objet [Nullable](../) spécifié, sinon - false

## Voir aussi

* Classe [Nullable](../)
* Structure [IsNullable](../../isnullable/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)