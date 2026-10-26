---
title: CompareExchange()
second_title: Référence API Aspose.Slides pour C++
description: "Échange conditionnel la valeur d'une variable : vérifie si la variable est égale à une valeur spécifique et enregistre la nouvelle valeur uniquement si la valeur stockée correspond à celle attendue."
type: docs
weight: 79
url: /fr/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T&, T, T) méthode


Échange conditionnel la valeur d’une variable : vérifie si la variable est égale à une valeur spécifique et enregistre la nouvelle valeur uniquement si la valeur stockée correspond à celle attendue.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Variable type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| location1 | T& | Variable reference to change. |
| value | T | Value to store. |
| comparand | T | Value to compare variable's value to before exchanging. |

### Valeur de retour

Valeur de la variable au début de l’opération, que celle-ci ait été modifiée ou non.

## Interlocked::CompareExchange(T&, T, T) méthode


Échange conditionnel la valeur d’une variable : vérifie si la variable est égale à une valeur spécifique et enregistre la nouvelle valeur uniquement si la valeur stockée correspond à celle attendue. Not implemented.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Variable type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| location1 | T& | Variable reference to change. |
| value | T | Value to store. |
| comparand | T | Value to compare variable's value to before exchanging. |

### Valeur de retour

Valeur de la variable au début de l’opération, que celle-ci ait été modifiée ou non.

## Interlocked::CompareExchange(int32_t&, int32_t, int32_t, bool&) méthode


Échange conditionnel la valeur d’une variable : vérifie si la variable est égale à une valeur spécifique et enregistre la nouvelle valeur uniquement si la valeur stockée correspond à celle attendue.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| location1 | **int32_t**& | Variable reference to change. |
| value | **int32_t** | Value to store. |
| comparand | **int32_t** | Value to compare variable's value to before exchanging. |
| succeeded | **bool**& | Référence à la variable qui est définie à true si l’échange a eu lieu et à false sinon. |

### Valeur de retour

Valeur de la variable au début de l’opération, que celle-ci ait été modifiée ou non.

## Voir aussi

* Classe [Interlocked](../)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)