---
title: Round()
second_title: Référence de l'API Aspose.Slides for C++
description: Arrondit la valeur spécifiée à l'entier le plus proche.
type: docs
weight: 157
url: /fr/system/math/round/
---
## Math::Round(double) méthode


Arrondit la valeur spécifiée à l'entier le plus proche.

```cpp
static double System::Math::Round(double a)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | **double** | La valeur à arrondir |

### Valeur retournée

**a** arrondi à l'entier le plus proche

## Math::Round(double, int) méthode


Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnels.

```cpp
static double System::Math::Round(double value, int digits)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **double** | La valeur à arrondir |
| digits | int | Le nombre de chiffres fractionnels dans la valeur arrondie |

### Valeur retournée

Le nombre avec le nombre de chiffres spécifié le plus proche de **value**

## Math::Round(double, MidpointRounding) méthode


Arrondit la valeur spécifiée à l'entier le plus proche. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **double** | La valeur à arrondir |
| mode | [MidpointRounding](../../midpointrounding/) | Spécifie comment effectuer l'arrondi si **value** est également proche de deux nombres les plus proches. |

### Valeur retournée

**value** arrondi à l'entier le plus proche

## Math::Round(double, int, MidpointRounding) méthode


Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnels. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **double** | La valeur à arrondir |
| digits | int | Le nombre de chiffres fractionnels dans la valeur arrondie |
| mode | [MidpointRounding](../../midpointrounding/) | Spécifie comment effectuer l'arrondi si **value** est également proche de deux nombres les plus proches. |

### Valeur retournée

Le nombre avec le nombre de chiffres spécifié le plus proche de **value**

## Math::Round(const Decimal\&) méthode


Arrondit la valeur spécifiée à l'entier le plus proche.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | La valeur à arrondir |

### Valeur retournée

**d** arrondi à l'entier le plus proche

## Math::Round(const Decimal\&, int) méthode


Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnels.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | La valeur à arrondir |
| digits | int | Le nombre de chiffres fractionnels dans la valeur arrondie |

### Valeur retournée

Le nombre avec le nombre de chiffres spécifié le plus proche de **value**

## Math::Round(const Decimal\&, MidpointRounding) méthode


Arrondit la valeur spécifiée à l'entier le plus proche. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | La valeur à arrondir |
| mode | [MidpointRounding](../../midpointrounding/) | Spécifie comment effectuer l'arrondi si **value** est également proche de deux nombres les plus proches. |

### Valeur retournée

**d** arrondi à l'entier le plus proche

## Math::Round(const Decimal\&, int, MidpointRounding) méthode


Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnels. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | La valeur à arrondir |
| digits | int | Le nombre de chiffres fractionnels dans la valeur arrondie |
| mode | [MidpointRounding](../../midpointrounding/) | Spécifie comment effectuer l'arrondi si **value** est également proche de deux nombres les plus proches. |

### Valeur retournée

Le nombre avec le nombre de chiffres spécifié le plus proche de **value**

## Voir aussi

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)