---
title: ColorTransformOperation
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'opération de transformation de couleur.
type: docs
weight: 5747
url: /fr/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum

Définit l'opération de transformation de couleur.

```cpp
enum class ColorTransformOperation
```

### Valeurs

| Name | Value | Description |
| --- | --- | --- |
| Tint | 0 | Teinte la couleur. Le paramètre est compris entre 0 (couleur originale) et 1 (blanc). |
| Shade | 1 | Assombrit la couleur. Le paramètre est compris entre 0 (couleur originale) et 1 (noir). |
| Complement | 2 | Modifie la couleur en une couleur complémentaire RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Modifie la couleur en une couleur inversée. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Convertit la couleur en une teinte de gris avec la même luminosité. Paramètre ignoré. |
| SetAlpha | 5 | Définit un composant alpha de la couleur. Le paramètre est compris entre 0 (transparent) et 1 (opaque). |
| AddAlpha | 6 | Ajoute la valeur du paramètre à un composant alpha de la couleur. Le paramètre est compris entre -1 et 1. |
| MultiplyAlpha | 7 | Multiplie un composant alpha par la valeur du paramètre. |
| SetHue | 8 | Modifie le composant teinte de la couleur selon la valeur du paramètre. Le paramètre est compris entre 0 et 360. |
| AddHue | 9 | Ajoute la valeur du paramètre au composant teinte de la couleur. Le paramètre est compris entre -360 et 360. |
| MultiplyHue | 10 | Multiplie le composant teinte par la valeur du paramètre. |
| SetSaturation | 11 | Modifie le composant saturation de la couleur selon la valeur du paramètre. Le paramètre est compris entre 0 et 1. |
| AddSaturation | 12 | Ajoute la valeur du paramètre au composant saturation de la couleur. Le paramètre est compris entre -1 et 1. |
| MultiplySaturation | 13 | Multiplie le composant saturation par la valeur du paramètre. |
| SetLuminance | 14 | Modifie le composant luminance de la couleur selon la valeur du paramètre. Le paramètre est compris entre 0 et 1. |
| AddLuminance | 15 | Ajoute la valeur du paramètre au composant luminance de la couleur. Le paramètre est compris entre -1 et 1. |
| MultiplyLuminance | 16 | Multiplie le composant luminance par la valeur du paramètre. |
| SetRed | 17 | Modifie le composant rouge de la couleur selon la valeur du paramètre. Le paramètre est compris entre 0 et 1. |
| AddRed | 18 | Ajoute la valeur du paramètre au composant rouge de la couleur. Le paramètre est compris entre -1 et 1. |
| MultiplyRed | 19 | Multiplie le composant rouge par le paramètre. |
| SetGreen | 20 | Modifie le composant vert de la couleur selon la valeur du paramètre. Le paramètre est compris entre 0 et 1. |
| AddGreen | 21 | Ajoute le paramètre au composant vert de la couleur. Le paramètre est compris entre -1 et 1. |
| MultiplyGreen | 22 | Multiplie le composant vert par la valeur du paramètre. |
| SetBlue | 23 | Modifie le composant bleu de la couleur selon la valeur du paramètre. Le paramètre est compris entre 0 et 360. |
| AddBlue | 24 | Ajoute la valeur du paramètre au composant bleu de la couleur. Le paramètre est compris entre -1 et 1. |
| MultiplyBlue | 25 | Multiplie le composant bleu par la valeur du paramètre. |
| Gamma | 26 | Correction gamma. Paramètre ignoré. |
| InverseGamma | 27 | Correction gamma inverse. Paramètre ignoré. |

## Voir aussi

* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)