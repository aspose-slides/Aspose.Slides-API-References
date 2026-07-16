---
title: Round()
second_title: Référence de l'API Aspose.Slides pour C++
description: Arrondit la valeur spécifiée au nombre entier le plus proche. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches.
type: docs
weight: 404
url: /fr/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) méthode

Arrondit la valeur spécifiée au nombre entier le plus proche. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | La valeur à arrondir |
| mode | [MidpointRounding](../../midpointrounding/) | Spécifie comment effectuer l’arrondi si **value** est également proche de deux nombres les plus proches. |

### Valeur de retour

**d** arrondi au nombre entier le plus proche

## Decimal::Round(const Decimal\&, int, MidpointRounding) méthode

Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnaires. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | La valeur à arrondir |
| digits | int | Le nombre de chiffres fractionnaires dans la valeur arrondie |
| mode | [MidpointRounding](../../midpointrounding/) | Spécifie comment effectuer l’arrondi si **value** est également proche de deux nombres les plus proches. |

### Valeur de retour

Le nombre avec le nombre de chiffres spécifié le plus proche de **value**

## Voir aussi

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Bibliothèque [Aspose.Slides](../../../)