---
title: Aspose.Slides.Effects
second_title: Référence API Aspose.Slides pour .NET
description: Contient des classes pour travailler avec divers effets dans les présentations Microsoft PowerPoint.
type: docs
weight: 50
url: /fr/aspose.slides.effects/
---

Contient des classes pour travailler avec divers effets dans les présentations Microsoft PowerPoint.

## Classes

| Classe | Description |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Représente un effet Alpha Bi-Level. Les valeurs Alpha (Opacité) inférieures au seuil sont changées en 0 (totalement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées en 100% (totalement opaque). |
| [AlphaCeiling](./alphaceiling) | Représente un effet Alpha Ceiling. Les valeurs Alpha (opacité) supérieures à zéro sont changées en 100%. En d'autres termes, tout ce qui est partiellement opaque devient totalement opaque. |
| [AlphaFloor](./alphafloor) | Représente un effet Alpha Floor. Les valeurs Alpha (opacité) inférieures à 100% sont changées en zéro. En d'autres termes, tout ce qui est partiellement transparent devient totalement transparent. |
| [AlphaInverse](./alphainverse) | Représente un effet Alpha Inverse. Les valeurs Alpha (opacité) sont inversées en soustrayant de 100%. |
| [AlphaModulate](./alphamodulate) | Représente un effet Alpha Modulate. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. Le conteneur d'effet spécifie un effet contenant des valeurs alpha à moduler. |
| [AlphaModulateFixed](./alphamodulatefixed) | Représente un effet Alpha Modulate Fixed. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. |
| [AlphaReplace](./alphareplace) | Représente un effet Alpha Replace. Les valeurs alpha (opacité) de l'effet sont remplacées par une alpha fixe. |
| [BiLevel](./bilevel) | Représente un effet Bi-Level (noir/blanc). Les couleurs d'entrée dont la luminance est inférieure à la valeur seuil spécifiée sont changées en noir. Les couleurs d'entrée dont la luminance est supérieure ou égale à la valeur spécifiée sont réglées sur blanc. Les valeurs d'effet alpha ne sont pas affectées par cet effet. |
| [Blur](./blur) | Représente un effet Blur qui est appliqué à l'ensemble de la forme, y compris son remplissage. Tous les canaux de couleur, y compris alpha, sont affectés. |
| [ColorChange](./colorchange) | Représente un effet Color Change. Les instances de FromColor sont remplacées par des instances de ToColor. |
| [ColorReplace](./colorreplace) | Représente un effet Color Replacement. Toutes les couleurs de l'effet sont changées en une couleur fixe. Les valeurs alpha ne sont pas affectées. |
| [Duotone](./duotone) | Représente un effet Duotone. Pour chaque pixel, combine Color1 et Color2 à travers une interpolation linéaire pour déterminer la nouvelle couleur pour ce pixel. |
| [EffectFactory](./effectfactory) | Permet de créer des effets |
| [FillOverlay](./filloverlay) | Représente un effet Fill Overlay. Un remplissage superposé peut être utilisé pour spécifier un remplissage supplémentaire pour un objet et mélanger les deux remplissages ensemble. |
| [Glow](./glow) | Représente un effet Glow, dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet. |
| [GrayScale](./grayscale) | Représente un effet Gray Scale. Convertit toutes les valeurs de couleur de l'effet en une teinte de gris, correspondant à leur luminance. Les valeurs alpha (opacité) de l'effet ne sont pas affectées. |
| [HSL](./hsl) | Représente un effet Hue/Saturation/Luminance. La teinte, la saturation et la luminance peuvent chacune être ajustées par rapport à leur valeur actuelle. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Objet immuable qui représente une collection en lecture seule d'effets de transformation d'image efficaces. |
| [ImageTransformOperation](./imagetransformoperation) | Représente un effet de transformation d'image abstrait. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Représente une collection d'effets appliqués à une image. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Permet de créer des opérations de transformation d'image |
| [InnerShadow](./innershadow) | Représente un effet Inner Shadow. |
| [Luminance](./luminance) | Représente un effet Luminance. La luminosité déplace linéairement toutes les couleurs plus près du blanc ou du noir. Le contraste échelonne toutes les couleurs pour être soit plus proches, soit plus éloignées. |
| [OuterShadow](./outershadow) | Représente un effet Outer Shadow. |
| [PresetShadow](./presetshadow) | Représente un effet Preset Shadow. |
| [Reflection](./reflection) | Représente un effet Reflection. |
| [SoftEdge](./softedge) | Représente un effet soft edge. Les bords de la forme sont flous, tandis que le remplissage n'est pas affecté. |
| [Tint](./tint) | Représente un effet Tint. Déplace les valeurs de couleur de l'effet vers/loin de la teinte d'un montant spécifié. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Représente un effet Alpha Bi-Level. Les valeurs Alpha (Opacité) inférieures au seuil sont changées en 0 (totalement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées en 100% (totalement opaque). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Objet immuable qui représente un effet Alpha Bi-Level. Les valeurs Alpha (Opacité) inférieures au seuil sont changées en 0 (totalement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées en 100% (totalement opaque). |
| [IAlphaCeiling](./ialphaceiling) | Représente un effet Alpha Ceiling. Les valeurs Alpha (opacité) supérieures à zéro sont changées en 100%. En d'autres termes, tout ce qui est partiellement opaque devient totalement opaque. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Objet immuable qui représente un effet Alpha Ceiling. Les valeurs Alpha (opacité) supérieures à zéro sont changées en 100%. En d'autres termes, tout ce qui est partiellement opaque devient totalement opaque. |
| [IAlphaFloor](./ialphafloor) | Représente un effet Alpha Floor. Les valeurs Alpha (opacité) inférieures à 100% sont changées en zéro. En d'autres termes, tout ce qui est partiellement transparent devient totalement transparent. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Objet immuable qui représente un effet Alpha Floor. Les valeurs Alpha (opacité) inférieures à 100% sont changées en zéro. En d'autres termes, tout ce qui est partiellement transparent devient totalement transparent. |
| [IAlphaInverse](./ialphainverse) | Représente un effet Alpha Inverse. Les valeurs Alpha (opacité) sont inversées en soustrayant de 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Objet immuable qui représente un effet Alpha Inverse. Les valeurs Alpha (opacité) sont inversées en soustrayant de 100%. |
| [IAlphaModulate](./ialphamodulate) | Représente un effet Alpha Modulate. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. Le conteneur d'effet spécifie un effet contenant des valeurs alpha à moduler. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Objet immuable qui représente un effet Alpha Modulate. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. Le conteneur d'effet spécifie un effet contenant des valeurs alpha à moduler. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Représente un effet Alpha Modulate Fixed. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Objet immuable qui représente un effet Alpha Modulate Fixed. Les valeurs alpha (opacité) de l'effet sont multipliées par un pourcentage fixe. |
| [IAlphaReplace](./ialphareplace) | Représente l'interface de base IImageTransformOperation. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Objet immuable qui représente un effet Alpha Replace. Les valeurs alpha (opacité) de l'effet sont remplacées par une alpha fixe. |
| [IBiLevel](./ibilevel) | Représente l'interface de base IImageTransformOperation. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Objet immuable qui représente un effet Bi-Level (noir/blanc). Les couleurs d'entrée dont la luminance est inférieure à la valeur seuil spécifiée sont changées en noir. Les couleurs d'entrée dont la luminance est supérieure ou égale à la valeur spécifiée sont réglées sur blanc. Les valeurs d'effet alpha ne sont pas affectées par cet effet. |
| [IBlur](./iblur) | Représente un effet Blur qui est appliqué à l'ensemble de la forme, y compris son remplissage. Tous les canaux de couleur, y compris alpha, sont affectés. |
| [IBlurEffectiveData](./iblureffectivedata) | Objet immuable qui représente un effet Blur qui est appliqué à l'ensemble de la forme, y compris son remplissage. Tous les canaux de couleur, y compris alpha, sont affectés. |
| [IColorChange](./icolorchange) | Représente un effet Color Change. Les instances de FromColor sont remplacées par des instances de ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Objet immuable qui représente un effet Color Change. Les instances de FromColor sont remplacées par des instances de ToColor. |
| [IColorReplace](./icolorreplace) | Représente un effet Color Replacement. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Objet immuable qui représente un effet Color Replacement. Toutes les couleurs de l'effet sont changées en une couleur fixe. Les valeurs alpha ne sont pas affectées. |
| [IDuotone](./iduotone) | Représente un effet Duotone. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Objet immuable qui représente un effet Duotone. Pour chaque pixel, combine clr1 et clr2 à travers une interpolation linéaire pour déterminer la nouvelle couleur pour ce pixel. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Classe de base pour les objets immuables, qui représentent un effet. |
| [IEffectFactory](./ieffectfactory) | Permet de créer des instances d'effets |
| [IFillOverlay](./ifilloverlay) | Représente un effet Fill Overlay. Un remplissage superposé peut être utilisé pour spécifier un remplissage supplémentaire pour un objet et mélanger les deux remplissages ensemble. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Objet immuable qui représente un effet Fill Overlay. Un remplissage superposé peut être utilisé pour spécifier un remplissage supplémentaire pour un objet et mélanger les deux remplissages ensemble. |
| [IGlow](./iglow) | Représente un effet Glow, dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet. |
| [IGlowEffectiveData](./igloweffectivedata) | Objet immuable qui représente un effet Glow, dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet. |
| [IGrayScale](./igrayscale) | Représente l'interface IImageTransformOperation. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Objet immuable qui représente un effet Gray Scale. Convertit toutes les valeurs de couleur de l'effet en une teinte de gris, correspondant à leur luminance. Les valeurs alpha (opacité) de l'effet ne sont pas affectées. |
| [IHSL](./ihsl) | Représente un effet Hue/Saturation/Luminance. La teinte, la saturation et la luminance peuvent chacune être ajustées par rapport à leur valeur actuelle. |
| [IHSLEffectiveData](./ihsleffectivedata) | Représente un effet Hue/Saturation/Luminance. La teinte, la saturation et la luminance peuvent chacune être ajustées par rapport à leur valeur actuelle. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Objet immuable qui représente une collection en lecture seule d'effets de transformation d'image efficaces. |
| [IImageTransformOperation](./iimagetransformoperation) | Représente un effet de transformation d'image abstrait. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Représente une collection d'effets appliqués à une image. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Permet de créer des instances d'effets de transformation d'image |
| [IInnerShadow](./iinnershadow) | Représente un effet de ombre intérieure. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Objet immuable qui représente un effet de ombre intérieure. |
| [ILuminance](./iluminance) | Représente un effet Luminance. La luminosité déplace linéairement toutes les couleurs plus près du blanc ou du noir. Le contraste échelonne toutes les couleurs pour être soit plus proches, soit plus éloignées. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Représente un effet Luminance. La luminosité déplace linéairement toutes les couleurs plus près du blanc ou du noir. Le contraste échelonne toutes les couleurs pour être soit plus proches, soit plus éloignées. |
| [IOuterShadow](./ioutershadow) | Représente un effet Outer Shadow. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Objet immuable qui représente un effet Outer Shadow. |
| [IPresetShadow](./ipresetshadow) | Représente un effet Preset Shadow. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Objet immuable qui représente un effet Preset Shadow. |
| [IReflection](./ireflection) | Représente un effet de réflexion. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Objet immuable qui représente un effet Reflection. |
| [ISoftEdge](./isoftedge) | Représente un effet Soft Edge. Les bords de la forme sont flous, tandis que le remplissage n'est pas affecté. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Objet immuable qui représente un effet de soft edge. Les bords de la forme sont flous, tandis que le remplissage n'est pas affecté. |
| [ITint](./itint) | Représente un effet Tint. Déplace les valeurs de couleur de l'effet vers/loin de la teinte d'un montant spécifié. |
| [ITintEffectiveData](./itinteffectivedata) | Objet immuable qui représente un effet Tint. Déplace les valeurs de couleur de l'effet vers/loin de la teinte d'un montant spécifié. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->