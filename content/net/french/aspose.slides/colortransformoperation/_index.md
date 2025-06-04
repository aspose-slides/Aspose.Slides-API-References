---  
title: ColorTransformOperation
second_title: Aspose.Slides pour .NET Référence de l'API  
description: Définit l'opération de transformation des couleurs.
type: docs  
weight: 2480  
url: /fr/aspose.slides/colortransformoperation/
---  
  
## Énumération ColorTransformOperation  
  
Définit l'opération de transformation des couleurs.  
  
```csharp  
public enum ColorTransformOperation  
```  
  
### Valeurs  
  
| Nom | Valeur | Description |  
| --- | --- | --- |  
| Tint | `0` | Teinte la couleur. Le paramètre est dans la plage entre 0 (couleur d'origine) et 1 (blanc). |  
| Shade | `1` | Ombre la couleur. Le paramètre est dans la plage entre 0 (couleur d'origine) et 1 (noir). |  
| Complement | `2` | Change la couleur en une couleur complémentaire RVB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |  
| Inverse | `3` | Change la couleur en une couleur inversée. r = 1 - r; g = 1 - g; b = 1 - b; |  
| Grayscale | `4` | Change la couleur en une couleur grise avec la même luminosité. Paramètre ignoré. |  
| SetAlpha | `5` | Définit un composant alpha de la couleur. Le paramètre est dans la plage entre 0 (transparent) et 1 (opaque). |  
| AddAlpha | `6` | Ajoute la valeur d'un paramètre à un composant alpha de la couleur. Le paramètre est dans la plage entre -1 et 1. |  
| MultiplyAlpha | `7` | Multiplie un composant alpha par la valeur d'un paramètre. |  
| SetHue | `8` | Change un composant de teinte de la couleur en une valeur de paramètre. Le paramètre est dans la plage entre 0 et 360. |  
| AddHue | `9` | Ajoute la valeur du paramètre au composant de teinte de la couleur. Le paramètre est dans la plage entre -360 et 360. |  
| MultiplyHue | `10` | Multiplie un composant de teinte par la valeur d'un paramètre. |  
| SetSaturation | `11` | Change un composant de saturation de la couleur en une valeur de paramètre. Le paramètre est dans la plage entre 0 et 1. |  
| AddSaturation | `12` | Ajoute la valeur d'un paramètre à un composant de saturation de la couleur. Le paramètre est dans la plage entre -1 et 1. |  
| MultiplySaturation | `13` | Multiplie un composant de saturation par la valeur d'un paramètre. |  
| SetLuminance | `14` | Change un composant de luminance de la couleur en une valeur de paramètre. Le paramètre est dans la plage entre 0 et 1. |  
| AddLuminance | `15` | Ajoute la valeur d'un paramètre à un composant de luminance de la couleur. Le paramètre est dans la plage entre -1 et 1. |  
| MultiplyLuminance | `16` | Multiplie un composant de luminance par la valeur d'un paramètre. |  
| SetRed | `17` | Change un composant rouge de la couleur en une valeur de paramètre. Le paramètre est dans la plage entre 0 et 1. |  
| AddRed | `18` | Ajoute la valeur d'un paramètre à un composant rouge de la couleur. Le paramètre est dans la plage entre -1 et 1. |  
| MultiplyRed | `19` | Multiplie un composant rouge par une valeur de paramètre. |  
| SetGreen | `20` | Change un composant vert de la couleur en une valeur de paramètre. Le paramètre est dans la plage entre 0 et 1. |  
| AddGreen | `21` | Ajoute un paramètre à un composant vert de la couleur. Le paramètre est dans la plage entre -1 et 1. |  
| MultiplyGreen | `22` | Multiplie un composant vert de la couleur par la valeur d'un paramètre. |  
| SetBlue | `23` | Change un composant bleu de la couleur en une valeur de paramètre. Le paramètre est dans la plage entre 0 et 360. |  
| AddBlue | `24` | Ajoute la valeur d'un paramètre à un composant bleu de la couleur. Le paramètre est dans la plage entre -1 et 1. |  
| MultiplyBlue | `25` | Multiplie un composant bleu de la couleur par la valeur d'un paramètre. |  
| Gamma | `26` | Correction gamma. Paramètre ignoré. |  
| InverseGamma | `27` | Correction gamma inverse. Paramètre ignoré. |  
  
### Voir aussi  
  
* namespace [Aspose.Slides](../../aspose.slides)  
* assembly [Aspose.Slides](../../)  