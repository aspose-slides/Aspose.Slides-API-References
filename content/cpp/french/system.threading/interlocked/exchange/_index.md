---
title: Exchange()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Échange la valeur d'une variable : stocke la nouvelle valeur et renvoie la valeur que la variable avait immédiatement avant le stockage."
type: docs
weight: 66
url: /fr/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) méthode


Échange la valeur d'une variable : stocke la nouvelle valeur et renvoie la valeur que la variable possédait immédiatement avant le stockage.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de variable. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| location1 | T\& | Référence de variable à modifier. |
| value | T | Valeur à stocker. |

### Valeur de retour

Valeur de la variable juste avant qu'elle ne soit modifiée.

## Interlocked::Exchange(T\&, T) méthode


Échange la valeur d'une variable : stocke la nouvelle valeur et renvoie la valeur que la variable possédait immédiatement avant le stockage. Non implémenté.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de variable. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| location1 | T\& | Référence de variable à modifier. |
| value | T | Valeur à stocker. |

### Valeur de retour

Valeur de la variable juste avant qu'elle ne soit modifiée.

## Voir aussi

* Classe [Interlocked](../)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)