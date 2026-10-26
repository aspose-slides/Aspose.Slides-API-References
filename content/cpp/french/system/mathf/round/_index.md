---
title: Round()
second_title: Référence de l'API Aspose.Slides pour C++
description: Arrondit la valeur spécifiée à la valeur entière la plus proche.
type: docs
weight: 157
url: /fr/system/mathf/round/
---
## MathF::Round(float) méthode


Arrondit la valeur spécifiée à la valeur entière la plus proche.

```cpp
static float System::MathF::Round(float a)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | **float** | La valeur à arrondir |

### Valeur de retour

**a** arrondi à la valeur entière la plus proche

## MathF::Round(float, int) méthode


Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnaires.

```cpp
static float System::MathF::Round(float value, int digits)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **float** | La valeur à arrondir |
| digits | int | Le nombre de chiffres fractionnaires dans la valeur arrondie |

### Valeur de retour

Le nombre avec le nombre de chiffres spécifié le plus proche de **value**

## MathF::Round(float, MidpointRounding) méthode


Arrondit la valeur spécifiée au nombre entier le plus proche. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **float** | La valeur à arrondir |
| mode | [MidpointRounding](../../midpointrounding/) | Spécifie comment effectuer l'arrondi si **value** est également proche de deux nombres les plus proches. |

### Valeur de retour

**value** arrondi au nombre entier le plus proche

## MathF::Round(float, int, MidpointRounding) méthode


Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnaires. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **float** | La valeur à arrondir |
| digits | int | Le nombre de chiffres fractionnaires dans la valeur arrondie |
| mode | [MidpointRounding](../../midpointrounding/) | Spécifie comment effectuer l'arrondi si **value** est également proche de deux nombres les plus proches. |

### Valeur de retour

Le nombre avec le nombre de chiffres spécifié le plus proche de **value**

## Voir aussi

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Espace de noms [System](../../)
* Library [Aspose.Slides](../../../)