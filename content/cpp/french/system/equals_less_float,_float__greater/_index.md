---
title: Equals< float, float >()
second_title: Référence API Aspose.Slides pour C++
description: "Spécialisation pour les valeurs à virgule flottante simple précision. Bien que deux NaN à virgule flottante soient définis par IEC 60559:1989 pour toujours être comparés comme différents, le contrat pour System.Object.Equals, exige que les surcharges respectent les exigences d'un opérateur d'équivalence. Ainsi, System.Double.Equals et System.Single.Equals renvoient True lors de la comparaison de deux NaN, tandis que l'opérateur d'égalité renvoie False dans ce cas, comme le requiert la norme."
type: docs
weight: 2666
url: /fr/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) fonction

Spécialisation pour les valeurs à virgule flottante simple précision. Bien que deux NaN à virgule flottante soient définis par IEC 60559:1989 pour toujours être considérés comme différents, le contrat pour [System.Object.Equals](../object/equals/), exige que les surcharge respectent les exigences d'un opérateur d'équivalence. Ainsi, System.Double.Equals et System.Single.Equals renvoient True lors de la comparaison de deux NaN, tandis que l'opérateur d'égalité renvoie False dans ce cas, comme l'exige la norme.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const **float**\& | Le premier comparand |
| b | const **float**\& | Le second comparand |

### Valeur de retour

True si les deux valeurs sont NaN ou sont égales, sinon - false

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)