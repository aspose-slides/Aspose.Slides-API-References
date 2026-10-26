---
title: Nullable()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une instance qui représente une valeur nulle.
type: docs
weight: 1
url: /fr/system/nullable/nullable/
---
## Nullable::Nullable() constructeur

Construit une instance qui représente une valeur nulle.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) constructeur

Construit une instance qui représente null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) constructeur

Construit une instance de la classe [Nullable](../) qui représente la valeur spécifiée convertie (si nécessaire) en la valeur du type sous-jacent T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type de la valeur spécifiée |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T1\& | Une référence constante à la valeur à représenter par le nouvel objet [Nullable](../) construit |

## Nullable::Nullable(const Nullable\<T1\>\&) constructeur

Construit une instance qui représente une valeur qui est représentée par l'objet [Nullable](../) spécifié. L'objet nullable spécifié peut représenter une valeur d'un type différent de celui du type sous-jacent de l'instance construite, auquel cas la valeur représentée est convertie en une valeur de type T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type de la valeur représentée par l'objet [Nullable](../) spécifié |

## Voir aussi

* Classe [Nullable](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)