---
title: Math
second_title: Référence de l'API Aspose.Slides pour C++
description: Contient des fonctions mathématiques. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.
type: docs
weight: 1756
url: /fr/system/math/
---
## Struct Math

Contient des fonctions mathématiques. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.

```cpp
class Math
```

## Méthodes

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | Renvoie la valeur absolue de la valeur spécifiée. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Renvoie la valeur absolue d'une valeur représentée par l'objet [Decimal](../decimal/) spécifié. |
| static **double** [Acos](./acos/)(**double**) | Calcule l'arccosinus de la valeur spécifiée. |
| static **double** [Asin](./asin/)(**double**) | Calcule l'arcsinus de la valeur spécifiée. |
| static **double** [Atan](./atan/)(**double**) | Calcule l'arctangente de la valeur spécifiée. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Calcule l'arctangente du rapport des valeurs spécifiées. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | Renvoie le produit complet de deux entiers 32 bits. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Renvoie la plus petite valeur entière supérieure ou égale à la valeur spécifiée. |
| static **double** [Ceiling](./ceiling/)(**double**) | Renvoie la plus petite valeur entière supérieure ou égale à la valeur spécifiée. |
| static **double** [Cos](./cos/)(**double**) | Calcule le cosinus de la valeur spécifiée. |
| static **double** [Cosh](./cosh/)(**double**) | Calcule le cosinus hyperbolique de la valeur spécifiée. |
| static int [DivRem](./divrem/)(int, int, int\&) | Calcule le quotient de deux entiers 32 bits ainsi que le reste. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | Calcule le quotient de deux entiers 64 bits ainsi que le reste. |
| static **double** [Exp](./exp/)(**double**) | Renvoie la constante e élevée à la puissance spécifiée. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Renvoie la plus grande valeur entière inférieure ou égale à la valeur spécifiée. |
| static **double** [Floor](./floor/)(**double**) | Renvoie la plus grande valeur entière inférieure ou égale à la valeur spécifiée. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Renvoie le reste résultant de la division d'un nombre spécifié par un autre nombre spécifié. |
| static **double** [Log](./log/)(**double**) | Renvoie le logarithme naturel de la valeur spécifiée. |
| static **double** [Log](./log/)(**double**, **double**) | Renvoie le logarithme de la valeur spécifiée dans la base spécifiée. |
| static **double** [Log10](./log10/)(**double**) | Renvoie le logarithme décimal (base 10) de la valeur spécifiée. |
| static auto [Max](./max/)(T0, T1) | Renvoie la plus grande valeur parmi les deux valeurs numériques spécifiées. |
| static T0 [Max](./max/)(T0, T1) | Renvoie la plus grande valeur parmi les deux valeurs numériques spécifiées. |
| **float** [Max_](./max_/)(**float**, **float**) | Renvoie la plus grande valeur à virgule flottante simple précision parmi les deux spécifiées. |
| **double** [Max_](./max_/)(**double**, **double**) | Renvoie la plus grande valeur à virgule flottante double précision parmi les deux spécifiées. |
| static auto [Min](./min/)(T0, T1) | Renvoie la plus petite valeur parmi les deux valeurs numériques spécifiées. |
| static T0 [Min](./min/)(T0, T1) | Renvoie la plus petite valeur parmi les deux valeurs numériques spécifiées. |
| **float** [Min_](./min_/)(**float**, **float**) | Renvoie la plus petite valeur à virgule flottante simple précision parmi les deux spécifiées. |
| **double** [Min_](./min_/)(**double**, **double**) | Renvoie la plus petite valeur à virgule flottante double précision parmi les deux spécifiées. |
| static T [Modulus](./modulus/)(T, T) | Calcule le reste résultant de la division d'une valeur spécifiée par une autre valeur spécifiée. |
| static **double** [Pow](./pow/)(**double**, **double**) | Renvoie la valeur spécifiée élevée à la puissance spécifiée. |
| static **double** [Round](./round/)(**double**) | Arrondit la valeur spécifiée à la valeur entière la plus proche. |
| static **double** [Round](./round/)(**double**, int) | Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnaires. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Arrondit la valeur spécifiée au nombre entier le plus proche. Un paramètre indique le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnaires. Un paramètre indique le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Arrondit la valeur spécifiée à la valeur entière la plus proche. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnaires. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Arrondit la valeur spécifiée au nombre entier le plus proche. Un paramètre indique le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre spécifié de chiffres fractionnaires. Un paramètre indique le comportement de la fonction si la valeur spécifiée est également proche de deux nombres les plus proches. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Détermine le signe de la valeur entière signée spécifiée. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Détermine le signe de la valeur flottante spécifiée. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Détermine le signe de la valeur décimale spécifiée. |
| static **double** [Sin](./sin/)(**double**) | Calcule le sinus de la valeur spécifiée. |
| static **double** [Sinh](./sinh/)(**double**) | Calcule le sinus hyperbolique de la valeur spécifiée. |
| static **double** [Sqrt](./sqrt/)(**double**) | Renvoie la racine carrée de la valeur spécifiée. |
| static **double** [Tan](./tan/)(**double**) | Calcule la tangente de la valeur spécifiée. |
| static **double** [Tanh](./tanh/)(**double**) | Calcule la tangente hyperbolique de la valeur spécifiée. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Renvoie l'objet [Decimal](../decimal/) représentant une valeur dont la partie entière est égale à celle de la valeur représentée par l'objet [Decimal](../decimal/) spécifié, avec tous les chiffres fractionnaires supprimés. |
| static **double** [Truncate](./truncate/)(**double**) | Renvoie une valeur à virgule flottante double précision dont la partie entière est égale à celle de la valeur spécifiée, tous les chiffres fractionnaires étant supprimés. |

## Champs

| Field | Description |
| --- | --- |
| static [E](./e/) | Base du logarithme naturel. |
| static [NaN](./nan/) | Représente une valeur NaN (not-a-number). |
| static [NegativeInfinity](./negativeinfinity/) | Représente l'infini négatif. |
| static [PI](./pi/) | Constante du nombre Pi. |
| static [PositiveInfinity](./positiveinfinity/) | Représente l'infini positif. |

## Remarques



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Affiche les valeurs absolues.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // Affiche le sinus de PI/2 et le cosinus de PI.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)