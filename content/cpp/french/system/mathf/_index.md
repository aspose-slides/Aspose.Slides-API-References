---
title: MathF
second_title: Référence API Aspose.Slides pour C++
description: Contient des fonctions mathématiques pour les valeurs à virgule flottante simple précision. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de ce type, quel que soit le moyen.
type: docs
weight: 1769
url: /fr/system/mathf/
---
## MathF struct

Contient des fonctions mathématiques pour les valeurs à virgule flottante simple précision. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de ce type, quel que soit le moyen.

```cpp
class MathF
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | Renvoie la valeur absolue de la valeur spécifiée. |
| static **float** [Acos](./acos/)(**float**) | Calcule l'arccosinus de la valeur spécifiée. |
| static **float** [Asin](./asin/)(**float**) | Calcule l'arcsinus de la valeur spécifiée. |
| static **float** [Atan](./atan/)(**float**) | Calcule l'arctangente de la valeur spécifiée. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Calcule l'arctangente du rapport des valeurs spécifiées. |
| static **float** [Ceiling](./ceiling/)(**float**) | Renvoie la plus petite valeur entière supérieure ou égale à la valeur spécifiée. |
| static **float** [Cos](./cos/)(**float**) | Calcule le cosinus de la valeur spécifiée. |
| static **float** [Cosh](./cosh/)(**float**) | Calcule le cosinus hyperbolique de la valeur spécifiée. |
| static **float** [Exp](./exp/)(**float**) | Renvoie la constante e élevée à la puissance spécifiée. |
| static **float** [Floor](./floor/)(**float**) | Renvoie la plus grande valeur entière inférieure ou égale à la valeur spécifiée. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Renvoie le reste résultant de la division du nombre spécifié par un autre nombre spécifié. |
| static **float** [Log](./log/)(**float**) | Renvoie le logarithme naturel de la valeur spécifiée. |
| static **float** [Log](./log/)(**float**, **float**) | Renvoie le logarithme de la valeur spécifiée dans la base spécifiée. |
| static **float** [Log10](./log10/)(**float**) | Renvoie le logarithme décimal (base 10) de la valeur spécifiée. |
| static **float** [Pow](./pow/)(**float**, **float**) | Renvoie la valeur spécifiée élevée à la puissance spécifiée. |
| static **float** [Round](./round/)(**float**) | Arrondit la valeur spécifiée à la valeur entière la plus proche. |
| static **float** [Round](./round/)(**float**, int) | Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnels. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Arrondit la valeur spécifiée à la valeur entière la plus proche. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnels. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnels. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Détermine le signe de la valeur entière signée spécifiée. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Détermine le signe de la valeur à virgule flottante spécifiée. |
| static **float** [Sin](./sin/)(**float**) | Calcule le sinus de la valeur spécifiée. |
| static **float** [Sinh](./sinh/)(**float**) | Calcule le sinus hyperbolique de la valeur spécifiée. |
| static **float** [Sqrt](./sqrt/)(**float**) | Renvoie la racine carrée de la valeur spécifiée. |
| static **float** [Tan](./tan/)(**float**) | Calcule la tangente de la valeur spécifiée. |
| static **float** [Tanh](./tanh/)(**float**) | Calcule la tangente hyperbolique de la valeur spécifiée. |
| static **float** [Truncate](./truncate/)(**float**) | Renvoie une valeur à virgule flottante simple précision dont la partie entière est égale à celle de la valeur spécifiée, tous les chiffres fractionnels étant supprimés. |

## Champs

| Champ | Description |
| --- | --- |
| static [E](./e/) | Base du logarithme naturel. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | Constante du nombre Pi. |
| static [Tau](./tau/) | Valeur de Tau. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)