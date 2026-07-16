---
title: MakeArray()
second_title: Référence API Aspose.Slides pour C++
description: Une fonction de fabrique qui construit un nouvel objet Array, le remplit avec les éléments de la liste d'initialisation spécifiée et renvoie un pointeur intelligent pointant vers l'objet Array.
type: docs
weight: 2003
url: /fr/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) fonction

Une fonction de fabrique qui construit un nouvel objet [Array](../array/), le remplit avec les éléments de la liste d'initialisation spécifiée et renvoie un pointeur intelligent pointant vers l'objet [Array](../array/).

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de l'objet [Array](../array/) que la fonction construit |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| init | std::initializer_list\<T\> | La liste d'initialisation contenant les éléments avec lesquels remplir le tableau |

### Valeur de retour

Un pointeur intelligent pointant vers l'objet [Array](../array/) construit

## System::MakeArray(Args\&&...) fonction

Une fonction de fabrique qui construit un nouvel objet [Array](../array/) en transmettant les arguments spécifiés à son constructeur.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de l'objet [Array](../array/) que la fonction construit |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Les arguments qui sont transmis au constructeur de l'objet [Array](../array/) en cours de construction |

### Valeur de retour

Un pointeur intelligent pointant vers l'objet [Array](../array/) construit

## System::MakeArray(Integral, Args\&&...) fonction

Une fonction de fabrique qui construit un nouvel objet [Array](../array/) en transmettant les arguments spécifiés à son constructeur.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de l'objet [Array](../array/) que la fonction construit |
| Integral | Type de la taille du tableau. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| size | Integral | Taille du tableau à créer. |
| args | Args\&&... | Les arguments qui sont transmis au constructeur de l'objet [Array](../array/) en cours de construction |

### Valeur de retour

Un pointeur intelligent pointant vers l'objet [Array](../array/) construit

## Voir Aussi

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)