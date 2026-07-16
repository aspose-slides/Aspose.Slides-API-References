---
title: Sign()
second_title: Référence API Aspose.Slides pour C++
description: Détermine le signe de la valeur entière signée spécifiée.
type: docs
weight: 274
url: /fr/system/mathf/sign/
---
## MathF::Sign(T) méthode

Détermine le signe de la valeur entière signée spécifiée.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type entier signé |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T | La valeur dont on détermine le signe |

### Valeur de retour

- 1 si **value** est inférieur à 0; 0 si **value** est égal à 0; 1 si **value** est supérieur à 0

## MathF::Sign(T) méthode

Détermine le signe de la valeur à virgule flottante spécifiée.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type à virgule flottante de l'argument |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T | La valeur dont on détermine le signe |

### Valeur de retour

- 1 si **value** est inférieur à 0; 0 si **value** est égal à 0; 1 si **value** est supérieur à 0

## Voir aussi

* Structure [MathF](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)