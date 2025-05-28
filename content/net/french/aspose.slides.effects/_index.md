---
title: Aspose.Slides.Effects
second_title: Référence de l'API Aspose.Slides pour .NET
description: Contient des classes pour travailler avec divers effets dans les présentations Microsoft PowerPoint.
type: docs
weight: 50
url: /fr/aspose.slides.effects/
---
Contient des classes pour travailler avec divers effets dans les présentations Microsoft PowerPoint.

## Des classes

| Classer | La description |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Représente un effet Alpha Bi-Level. Les valeurs Alpha (Opacité) inférieures au seuil sont changées en 0 (entièrement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées en 100 % (entièrement opaque). |
| [AlphaCeiling](./alphaceiling) | Représente un effet de plafond alpha. Les valeurs alpha (opacité) supérieures à zéro sont remplacées par 100 %. En d'autres termes, tout ce qui est partiellement opaque devient complètement opaque. |
| [AlphaFloor](./alphafloor) | Représente un effet Alpha Floor. Les valeurs Alpha (opacité) inférieures à 100 % sont remplacées par zéro. En d'autres termes, tout ce qui est partiellement transparent devient entièrement transparent. |
| [AlphaInverse](./alphainverse) | Représente un effet Alpha Inverse. Les valeurs Alpha (opacité) sont inversées en soustrayant de 100 %. |
| [AlphaModulate](./alphamodulate) | Représente un effet de modulation alpha. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. Le conteneur d'effet spécifie un effet contenant des valeurs alpha à moduler. |
| [AlphaModulateFixed](./alphamodulatefixed) | Représente un effet fixe de modulation alpha. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. |
| [AlphaReplace](./alphareplace) | Représente et remplace l'effet Alpha. Les valeurs alpha (opacité) de l'effet sont remplacées par un alpha fixe. |
| [BiLevel](./bilevel) | Représente un effet Bi-Level (noir/blanc). Les couleurs d'entrée dont la luminance est inférieure à la valeur de seuil spécifiée sont modifiées en noir. Les couleurs d'entrée dont la luminance est supérieure ou égale à la valeur spécifiée sont définies sur blanc. Le les valeurs d'effet alpha ne sont pas affectées par cet effet. |
| [Blur](./blur) | Représente un effet de flou appliqué à l'ensemble de la forme, y compris son remplissage. Tous les canaux de couleur, y compris alpha, sont affectés. |
| [ColorChange](./colorchange) | Représente un effet de changement de couleur. Les instances de FromColor sont remplacées par des instances de ToColor. |
| [ColorReplace](./colorreplace) | Représente un effet de remplacement de couleur. Toutes les couleurs d'effet sont remplacées par une couleur fixe. Les valeurs alpha ne sont pas affectées. |
| [Duotone](./duotone) | Représente un effet Duotone. Pour chaque pixel, combine Color1 et Color2 via une interpolation linéaire pour déterminer la nouvelle couleur de ce pixel. |
| [EffectFactory](./effectfactory) | Permet de créer des effets |
| [FillOverlay](./filloverlay) | Représente un effet Fill Overlay. Une superposition de remplissage peut être utilisée pour spécifier un remplissage supplémentaire pour un objet et mélanger les deux remplissages ensemble. |
| [Glow](./glow) | Représente un effet Glow, dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet. |
| [GrayScale](./grayscale) | Représente un effet d'échelle de gris. Convertit toutes les valeurs de couleur d'effet en une nuance de gris, correspondant à leur luminance. Les valeurs d'effet alpha (opacité) ne sont pas affectées. |
| [HSL](./hsl) | Représente un effet Teinte/Saturation/Luminance. La teinte, la saturation et la luminance peuvent chacune être ajustées par rapport à sa valeur actuelle. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Objet immuable qui représente une collection en lecture seule d'effets de transformation d'image effectifs. |
| [ImageTransformOperation](./imagetransformoperation) | Représente l'effet de transformation d'image abstraite. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Représente une collection d'effets appliqués à une image. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Permet de créer des opérations de transformation d'image |
| [InnerShadow](./innershadow) | Représente un effet Inner Shadow. |
| [Luminance](./luminance) | Représente un effet de luminance. La luminosité décale linéairement toutes les couleurs vers le blanc ou le noir. Le contraste met à l'échelle toutes les couleurs pour qu'elles soient plus proches ou plus éloignées. |
| [OuterShadow](./outershadow) | Représente un effet d'ombre extérieure. |
| [PresetShadow](./presetshadow) | Représente un effet d'ombre prédéfini. |
| [Reflection](./reflection) | Représente un effet de réflexion. |
| [SoftEdge](./softedge) | Représente un effet de bord doux. Les bords de la forme sont flous, tandis que le remplissage n'est pas affecté. |
| [Tint](./tint) | Représente un effet de teinte. Déplace les valeurs de couleur d'effet vers/à partir de la teinte de la quantité spécifiée. |
## Interfaces

| Interface | La description |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Représente un effet Alpha Bi-Level. Les valeurs Alpha (Opacité) inférieures au seuil sont changées en 0 (entièrement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées en 100 % (entièrement opaque). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Objet immuable qui représente un effet Alpha Bi-Level. Les valeurs Alpha (Opacité) inférieures au seuil sont changées en 0 (entièrement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées en 100 % (entièrement opaque). |
| [IAlphaCeiling](./ialphaceiling) | Représente un effet de plafond alpha. Les valeurs alpha (opacité) supérieures à zéro sont remplacées par 100 %. En d'autres termes, tout ce qui est partiellement opaque devient complètement opaque. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Objet immuable qui représente un effet de plafond alpha. Les valeurs alpha (opacité) supérieures à zéro sont remplacées par 100 %. En d'autres termes, tout ce qui est partiellement opaque devient totalement opaque. |
| [IAlphaFloor](./ialphafloor) | Représente un effet Alpha Floor. Les valeurs Alpha (opacité) inférieures à 100 % sont remplacées par zéro. En d'autres termes, tout ce qui est partiellement transparent devient entièrement transparent. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Objet immuable qui représente un effet Alpha Floor. Les valeurs Alpha (opacité) inférieures à 100 % sont remplacées par zéro. En d'autres termes, tout ce qui est partiellement transparent devient entièrement transparent. |
| [IAlphaInverse](./ialphainverse) | Représente un effet Alpha Inverse. Les valeurs Alpha (opacité) sont inversées en soustrayant de 100 %. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Objet immuable qui représente un effet Alpha Inverse. Les valeurs Alpha (opacité) sont inversées en soustrayant de 100 %. |
| [IAlphaModulate](./ialphamodulate) | Représente un effet de modulation alpha. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. Le conteneur d'effet spécifie un effet contenant des valeurs alpha à moduler. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Objet immuable qui représente un effet de modulation alpha. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. Le conteneur d'effet spécifie un effet contenant des valeurs alpha à moduler. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Représente un effet fixe de modulation alpha. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Objet immuable qui représente un effet Alpha Modulate Fixed. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. |
| [IAlphaReplace](./ialphareplace) | Représente l'interface IImageTransformOperation de base. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Objet immuable qui représente un effet de remplacement alpha. Les valeurs alpha (opacité) de l'effet sont remplacées par un alpha fixe. |
| [IBiLevel](./ibilevel) | Représente l'interface IImageTransformOperation de base. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Objet immuable qui représente un effet Bi-Level (noir/blanc). Les couleurs d'entrée dont la luminance est inférieure à la valeur de seuil spécifiée sont changées en noir. Les couleurs d'entrée dont la luminance est supérieure ou égale à la valeur spécifiée sont définies sur blanc . Les valeurs de l'effet alpha ne sont pas affectées par cet effet. |
| [IBlur](./iblur) | Représente un effet de flou appliqué à l'ensemble de la forme, y compris son remplissage. Tous les canaux de couleur, y compris alpha, sont affectés. |
| [IBlurEffectiveData](./iblureffectivedata) | Objet immuable qui représente un effet de flou appliqué à l'ensemble de la forme, y compris son remplissage. Tous les canaux de couleur, y compris alpha, sont affectés. |
| [IColorChange](./icolorchange) | Représente un effet de changement de couleur. Les instances de FromColor sont remplacées par des instances de ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Objet immuable qui représente un effet de changement de couleur. Les instances de FromColor sont remplacées par des instances de ToColor. |
| [IColorReplace](./icolorreplace) | Représente un effet de remplacement de couleur. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Objet immuable qui représente un effet de remplacement de couleur. Toutes les couleurs d'effet sont remplacées par une couleur fixe. Les valeurs alpha ne sont pas affectées. |
| [IDuotone](./iduotone) | Représente un effet Duotone. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Objet immuable qui représente un effet Duotone. Pour chaque pixel, combine clr1 et clr2 via une interpolation linéaire pour déterminer la nouvelle couleur de ce pixel. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Classe de base pour les objets immuables, qui représentent l'effet. |
| [IEffectFactory](./ieffectfactory) | Permet de créer des instances d'effets |
| [IFillOverlay](./ifilloverlay) | Représente un effet Fill Overlay. Une superposition de remplissage peut être utilisée pour spécifier un remplissage supplémentaire pour un objet et mélanger les deux remplissages ensemble. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Objet immuable qui représente un effet Fill Overlay. Une superposition de remplissage peut être utilisée pour spécifier un remplissage supplémentaire pour un objet et mélanger les deux remplissages ensemble. |
| [IGlow](./iglow) | Représente un effet Glow, dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet. |
| [IGlowEffectiveData](./igloweffectivedata) | Objet immuable qui représente un effet Glow, dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet. |
| [IGrayScale](./igrayscale) | Représente l'interface IImageTransformOperation. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Objet immuable qui représente un effet d'échelle de gris. Convertit toutes les valeurs de couleur d'effet en une nuance de gris, correspondant à leur luminance. Les valeurs d'effet alpha (opacité) ne sont pas affectées. |
| [IHSL](./ihsl) | Représente un effet Teinte/Saturation/Luminance. La teinte, la saturation et la luminance peuvent chacune être ajustées par rapport à sa valeur actuelle. |
| [IHSLEffectiveData](./ihsleffectivedata) | Représente un effet Teinte/Saturation/Luminance. La teinte, la saturation et la luminance peuvent chacune être ajustées par rapport à sa valeur actuelle. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Objet immuable qui représente une collection en lecture seule d'effets de transformation d'image effectifs. |
| [IImageTransformOperation](./iimagetransformoperation) | Représente l'effet de transformation d'image abstraite. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Représente une collection d'effets appliqués à une image. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Permet de créer des instances d'effets d'image |
| [IInnerShadow](./iinnershadow) | Représente un effet d'ombre intérieure. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Objet immuable qui représente un effet d'ombre intérieure. |
| [ILuminance](./iluminance) | Représente un effet de luminance. La luminosité décale linéairement toutes les couleurs vers le blanc ou le noir. Le contraste met à l'échelle toutes les couleurs pour qu'elles soient plus proches ou plus éloignées. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Représente un effet de luminance. La luminosité décale linéairement toutes les couleurs vers le blanc ou le noir. Le contraste met à l'échelle toutes les couleurs pour qu'elles soient plus proches ou plus éloignées. |
| [IOuterShadow](./ioutershadow) | Représente un effet d'ombre extérieure. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Objet immuable qui représente un effet d'ombre extérieure. |
| [IPresetShadow](./ipresetshadow) | Représente un effet d'ombre prédéfini. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Objet immuable qui représente un effet d'ombre prédéfini. |
| [IReflection](./ireflection) | Représente un effet de réflexion. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Objet immuable qui représente un effet de réflexion. |
| [ISoftEdge](./isoftedge) | Représente un effet Soft Edge. Les bords de la forme sont flous, tandis que le remplissage n'est pas affecté. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Objet immuable qui représente un effet de bord doux. Les bords de la forme sont flous, tandis que le remplissage n'est pas affecté. |
| [ITint](./itint) | Représente un effet de teinte. Déplace les valeurs de couleur d'effet vers/à partir de la teinte de la quantité spécifiée. |
| [ITintEffectiveData](./itinteffectivedata) | Objet immuable qui représente un effet de teinte. Déplace les valeurs de couleur d'effet vers/à partir de la teinte de la quantité spécifiée. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
