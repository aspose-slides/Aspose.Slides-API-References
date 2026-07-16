---
title: RoundImpl()
second_title: Référence de l'API Aspose.Slides pour C++
description: Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnaires. Un paramètre indique le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches.
type: docs
weight: 287
url: /fr/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) méthode


Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnaires. Un paramètre indique le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **float** | La valeur à arrondir |
| digits | int | Le nombre de chiffres fractionnaires dans la valeur arrondie |
| mode | [MidpointRounding](../../midpointrounding/) | Spécifie comment effectuer l'arrondi si **value** est également proche de deux nombres les plus proches. |

### Valeur de retour

Le nombre avec le nombre spécifié de chiffres le plus proche de **value**

## Voir aussi

* Énum [MidpointRounding](../../midpointrounding/)
* Structure [MathF](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)