---
title: Aspose.Slides.Effects
second_title: Aspose.Slides pour API .NET Référence
description: Contient des classes pour travailler avec divers effets dans les présentations Microsoft PowerPoint.
type: docs
weight: 50
url: /fr/aspose.slides.effects/
---

Contient des classes pour travailler avec divers effets dans les présentations Microsoft PowerPoint.

## Classes

| Classe | Description |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Représente un effet Alpha Bi-Niveau. Les valeurs Alpha (Opacité) inférieures au seuil sont changées en 0 (entièrement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées en 100% (entièrement opaque). |
| [AlphaCeiling](./alphaceiling) | Représente un effet Alpha Ceiling. Les valeurs Alpha (opacité) supérieures à zéro sont changées en 100%. En d'autres termes, tout ce qui est partiellement opaque devient entièrement opaque. |
| [AlphaFloor](./alphafloor) | Représente un effet Alpha Floor. Les valeurs Alpha (opacité) inférieures à 100% sont changées en zéro. En d'autres termes, tout ce qui est partiellement transparent devient entièrement transparent. |
| [AlphaInverse](./alphainverse) | Représente un effet Alpha Inverse. Les valeurs Alpha (opacité) sont inversées en soustrayant de 100%. |
| [AlphaModulate](./alphamodulate) | Représente un effet Alpha Modulate. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. Le conteneur d'effet spécifie un effet contenant des valeurs alpha à moduler. |
| [AlphaModulateFixed](./alphamodulatefixed) | Représente un effet Alpha Modulate Fixed. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. |
| [AlphaReplace](./alphareplace) | Représente un effet Alpha Replace. Les valeurs alpha (opacité) de l'effet sont remplacées par un alpha fixe. |
| [BiLevel](./bilevel) | Représente un effet Bi-Niveau (noir/blanc). Les couleurs d'entrée dont la luminance est inférieure à la valeur seuil spécifiée sont changées en noir. Les couleurs d'entrée dont la luminance est supérieure ou égale à la valeur spécifiée sont définies sur blanc. Les valeurs alpha de l'effet ne sont pas affectées par cet effet. |
| [Blur](./blur) | Représente un effet de flou qui est appliqué à l'ensemble de la forme, y compris son remplissage. Tous les canaux de couleur, y compris alpha, sont affectés. |
| [ColorChange](./colorchange) | Représente un effet de changement de couleur. Les instances de FromColor sont remplacées par des instances de ToColor. |
| [ColorReplace](./colorreplace) | Représente un effet de remplacement de couleur. Toutes les couleurs de l'effet sont changées en une couleur fixe. Les valeurs alpha ne sont pas affectées. |
| [Duotone](./duotone) | Représente un effet Duotone. Pour chaque pixel, combine Color1 et Color2 par interpolation linéaire pour déterminer la nouvelle couleur de ce pixel. |
| [EffectFactory](./effectfactory) | Permet de créer des effets |
| [FillOverlay](./filloverlay) | Représente un effet de remplissage superposé. Un remplissage superposé peut être utilisé pour spécifier un remplissage supplémentaire pour un objet et mélanger les deux remplissages ensemble. |
| [Glow](./glow) | Représente un effet de lueur, dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet. |
| [GrayScale](./grayscale) | Représente un effet de niveaux de gris. Convertit toutes les valeurs de couleur de l'effet en une nuance de gris, correspondant à leur luminance. Les valeurs alpha (opacité) de l'effet ne sont pas affectées. |
| [HSL](./hsl) | Représente un effet de Teinte/Saturation/Luminance. La teinte, la saturation et la luminance peuvent chacune être ajustées par rapport à leur valeur actuelle. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Objet immutable qui représente une collection en lecture seule d'effets de transformation d'image effectifs. |
| [ImageTransformOperation](./imagetransformoperation) | Représente un effet de transformation d'image abstrait. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Représente une collection d'effets appliqués à une image. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Permet de créer des opérations de transformation d'image |
| [InnerShadow](./innershadow) | Représente un effet d'ombre interne. |
| [Luminance](./luminance) | Représente un effet de luminance. La luminosité déplace linéairement toutes les couleurs plus près du blanc ou du noir. Le contraste échelle toutes les couleurs pour être soit plus proches soit plus éloignées. |
| [OuterShadow](./outershadow) | Représente un effet d'ombre externe. |
| [PresetShadow](./presetshadow) | Représente un effet d'ombre prédéfini. |
| [Reflection](./reflection) | Représente un effet de réflexion. |
| [SoftEdge](./softedge) | Représente un effet de bord doux. Les bords de la forme sont flous, tandis que le remplissage n'est pas affecté. |
| [Tint](./tint) | Représente un effet de teinte. Déplace les valeurs de couleur de l'effet vers/loin de la teinte par le montant spécifié. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Représente un effet Alpha Bi-Niveau. Les valeurs Alpha (Opacité) inférieures au seuil sont changées en 0 (entièrement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées en 100% (entièrement opaque). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Objet immutable qui représente un effet Alpha Bi-Niveau. Les valeurs Alpha (Opacité) inférieures au seuil sont changées en 0 (entièrement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées en 100% (entièrement opaque). |
| [IAlphaCeiling](./ialphaceiling) | Représente un effet Alpha Ceiling. Les valeurs Alpha (opacité) supérieures à zéro sont changées en 100%. En d'autres termes, tout ce qui est partiellement opaque devient entièrement opaque. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Objet immutable qui représente un effet Alpha Ceiling. Les valeurs Alpha (opacité) supérieures à zéro sont changées en 100%. En d'autres termes, tout ce qui est partiellement opaque devient entièrement opaque. |
| [IAlphaFloor](./ialphafloor) | Représente un effet Alpha Floor. Les valeurs Alpha (opacité) inférieures à 100% sont changées en zéro. En d'autres termes, tout ce qui est partiellement transparent devient entièrement transparent. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Objet immutable qui représente un effet Alpha Floor. Les valeurs Alpha (opacité) inférieures à 100% sont changées en zéro. En d'autres termes, tout ce qui est partiellement transparent devient entièrement transparent. |
| [IAlphaInverse](./ialphainverse) | Représente un effet Alpha Inverse. Les valeurs Alpha (opacité) sont inversées en soustrayant de 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Objet immutable qui représente un effet Alpha Inverse. Les valeurs Alpha (opacité) sont inversées en soustrayant de 100%. |
| [IAlphaModulate](./ialphamodulate) | Représente un effet Alpha Modulate. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. Le conteneur d'effet spécifie un effet contenant des valeurs alpha à moduler. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Objet immutable qui représente un effet Alpha Modulate. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. Le conteneur d'effet spécifie un effet contenant des valeurs alpha à moduler. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Représente un effet Alpha Modulate Fixed. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Objet immutable qui représente un effet Alpha Modulate Fixed. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. |
| [IAlphaReplace](./ialphareplace) | Représente l'interface de base IImageTransformOperation. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Objet immutable qui représente un effet Alpha Replace. Les valeurs alpha (opacité) de l'effet sont remplacées par un alpha fixe. |
| [IBiLevel](./ibilevel) | Représente l'interface de base IImageTransformOperation. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Objet immutable qui représente un effet Bi-Niveau (noir/blanc). Les couleurs d'entrée dont la luminance est inférieure à la valeur seuil spécifiée sont changées en noir. Les couleurs d'entrée dont la luminance est supérieure ou égale à la valeur spécifiée sont définies sur blanc. Les valeurs alpha de l'effet ne sont pas affectées par cet effet. |
| [IBlur](./iblur) | Représente un effet de flou qui est appliqué à l'ensemble de la forme, y compris son remplissage. Tous les canaux de couleur, y compris alpha, sont affectés. |
| [IBlurEffectiveData](./iblureffectivedata) | Objet immutable qui représente un effet de flou qui est appliqué à l'ensemble de la forme, y compris son remplissage. Tous les canaux de couleur, y compris alpha, sont affectés. |
| [IColorChange](./icolorchange) | Représente un effet de changement de couleur. Les instances de FromColor sont remplacées par des instances de ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Objet immutable qui représente un effet de changement de couleur. Les instances de FromColor sont remplacées par des instances de ToColor. |
| [IColorReplace](./icolorreplace) | Représente un effet de remplacement de couleur. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Objet immutable qui représente un effet de remplacement de couleur. Toutes les couleurs de l'effet sont changées en une couleur fixe. Les valeurs alpha ne sont pas affectées. |
| [IDuotone](./iduotone) | Représente un effet Duotone. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Objet immutable qui représente un effet Duotone. Pour chaque pixel, combine clr1 et clr2 par interpolation linéaire pour déterminer la nouvelle couleur de ce pixel. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Classe de base pour les objets immuables, qui représentent l'effet. |
| [IEffectFactory](./ieffectfactory) | Permet de créer des instances d'effets |
| [IFillOverlay](./ifilloverlay) | Représente un effet de remplissage superposé. Un remplissage superposé peut être utilisé pour spécifier un remplissage supplémentaire pour un objet et mélanger les deux remplissages ensemble. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Objet immutable qui représente un effet de remplissage superposé. Un remplissage superposé peut être utilisé pour spécifier un remplissage supplémentaire pour un objet et mélanger les deux remplissages ensemble. |
| [IGlow](./iglow) | Représente un effet de lueur, dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet. |
| [IGlowEffectiveData](./igloweffectivedata) | Objet immutable qui représente un effet de lueur, dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet. |
| [IGrayScale](./igrayscale) | Représente l'interface IImageTransformOperation. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Objet immutable qui représente un effet de niveaux de gris. Convertit toutes les valeurs de couleur de l'effet en une nuance de gris, correspondant à leur luminance. Les valeurs alpha (opacité) de l'effet ne sont pas affectées. |
| [IHSL](./ihsl) | Représente un effet de Teinte/Saturation/Luminance. La teinte, la saturation et la luminance peuvent chacune être ajustées par rapport à leur valeur actuelle. |
| [IHSLEffectiveData](./ihsleffectivedata) | Représente un effet de Teinte/Saturation/Luminance. La teinte, la saturation et la luminance peuvent chacune être ajustées par rapport à leur valeur actuelle. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Objet immutable qui représente une collection en lecture seule d'effets de transformation d'image effectifs. |
| [IImageTransformOperation](./iimagetransformoperation) | Représente un effet de transformation d'image abstrait. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Représente une collection d'effets appliqués à une image. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Permet de créer des instances d'effets d'image |
| [IInnerShadow](./iinnershadow) | Représente un effet d'ombre interne. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Objet immutable qui représente un effet d'ombre interne. |
| [ILuminance](./iluminance) | Représente un effet de luminance. La luminosité déplace linéairement toutes les couleurs plus près du blanc ou du noir. Le contraste échelle toutes les couleurs pour être soit plus proches soit plus éloignées. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Représente un effet de luminance. La luminosité déplace linéairement toutes les couleurs plus près du blanc ou du noir. Le contraste échelle toutes les couleurs pour être soit plus proches soit plus éloignées. |
| [IOuterShadow](./ioutershadow) | Représente un effet d'ombre externe. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Objet immutable qui représente un effet d'ombre externe. |
| [IPresetShadow](./ipresetshadow) | Représente un effet d'ombre prédéfini. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Objet immutable qui représente un effet d'ombre prédéfini. |
| [IReflection](./ireflection) | Représente un effet de réflexion. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Objet immutable qui représente un effet de réflexion. |
| [ISoftEdge](./isoftedge) | Représente un effet de bord doux. Les bords de la forme sont flous, tandis que le remplissage n'est pas affecté. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Objet immutable qui représente un effet de bord doux. Les bords de la forme sont flous, tandis que le remplissage n'est pas affecté. |
| [ITint](./itint) | Représente un effet de teinte. Déplace les valeurs de couleur de l'effet vers/loin de la teinte par le montant spécifié. |
| [ITintEffectiveData](./itinteffectivedata) | Objet immutable qui représente un effet de teinte. Déplace les valeurs de couleur de l'effet vers/loin de la teinte par le montant spécifié. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->