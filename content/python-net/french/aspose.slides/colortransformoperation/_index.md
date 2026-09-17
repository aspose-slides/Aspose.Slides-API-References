---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/colortransformoperation/
---
## ColorTransformOperation énumération

Définit l'opération de transformation de couleur.

Le type ColorTransformOperation expose les membres suivants :

## Champs

| Champ | Description |
| :- | :- |
| TINT | Teinte la couleur. Le paramètre est compris entre 0 (couleur originale) et 1 (blanc). |
| SHADE | Assombrit la couleur. Le paramètre est compris entre 0 (couleur originale) et 1 (noir). |
| COMPLEMENT | Modifie la couleur pour obtenir une couleur complémentaire RVB.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | Modifie la couleur pour obtenir une couleur inversée.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | Modifie la couleur pour obtenir un gris avec la même luminosité. Paramètre ignoré. |
| SET_ALPHA | Définit le composant alpha de la couleur. Le paramètre est compris entre 0 (transparent) et 1 (opaque). |
| ADD_ALPHA | Ajoute la valeur du paramètre au composant alpha de la couleur. Le paramètre est compris entre -1 et 1. |
| MULTIPLY_ALPHA | Multiplie le composant alpha par la valeur du paramètre. |
| SET_HUE | Modifie le composant teinte de la couleur à la valeur du paramètre. Le paramètre est compris entre 0 et 360. |
| ADD_HUE | Ajoute la valeur du paramètre au composant teinte de la couleur. Le paramètre est compris entre -360 et 360. |
| MULTIPLY_HUE | Multiplie le composant teinte par la valeur du paramètre. |
| SET_SATURATION | Modifie le composant saturation de la couleur à la valeur du paramètre. Le paramètre est compris entre 0 et 1. |
| ADD_SATURATION | Ajoute la valeur du paramètre au composant saturation de la couleur. Le paramètre est compris entre -1 et 1. |
| MULTIPLY_SATURATION | Multiplie le composant saturation par la valeur du paramètre. |
| SET_LUMINANCE | Modifie le composant luminance de la couleur à la valeur du paramètre. Le paramètre est compris entre 0 et 1. |
| ADD_LUMINANCE | Ajoute la valeur du paramètre au composant luminance de la couleur. Le paramètre est compris entre -1 et 1. |
| MULTIPLY_LUMINANCE | Multiplie le composant luminance par la valeur du paramètre. |
| SET_RED | Modifie le composant rouge de la couleur à la valeur du paramètre. Le paramètre est compris entre 0 et 1. |
| ADD_RED | Ajoute la valeur du paramètre au composant rouge de la couleur. Le paramètre est compris entre -1 et 1. |
| MULTIPLY_RED | Multiplie le composant rouge par le paramètre. |
| SET_GREEN | Modifie le composant vert de la couleur à la valeur du paramètre. Le paramètre est compris entre 0 et 1. |
| ADD_GREEN | Ajoute le paramètre au composant vert de la couleur. Le paramètre est compris entre -1 et 1. |
| MULTIPLY_GREEN | Multiplie le composant vert par la valeur du paramètre. |
| SET_BLUE | Modifie le composant bleu de la couleur à la valeur du paramètre. Le paramètre est compris entre 0 et 360. |
| ADD_BLUE | Ajoute la valeur du paramètre au composant bleu de la couleur. Le paramètre est compris entre -1 et 1. |
| MULTIPLY_BLUE | Multiplie le composant bleu par la valeur du paramètre. |
| GAMMA | Correction gamma. Paramètre ignoré. |
| INVERSE_GAMMA | Correction gamma inverse. Paramètre ignoré. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)