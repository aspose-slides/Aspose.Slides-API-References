---
title: Default()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la référence à l'unique instance construite par défaut du type d'exception.
type: docs
weight: 2198
url: /fr/system/default/
---
## System::Default() fonction

Renvoie la référence à l'unique instance construite par défaut du type d'exception.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type dont l'instance est renvoyée |

## System::Default() fonction

Renvoie la référence à l'unique instance construite par défaut du type non exception.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type dont l'instance est renvoyée |

## Voir aussi

* Structure [IsExceptionWrapper](../isexceptionwrapper/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)