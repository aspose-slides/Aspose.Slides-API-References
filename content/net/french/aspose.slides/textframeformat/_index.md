---
title: TextFrameFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Contient les propriétés formatTextFrameFormatting de TextFrame.
type: docs
weight: 10210
url: /fr/aspose.slides/textframeformat/
---
## TextFrameFormat class

Contient les propriétés formatTextFrameFormatting de TextFrame.

```csharp
public class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Initialise une nouvelle instance de[`TextFrameFormat`](../textframeformat) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Renvoie ou définit un texte d'ancrage vertical dans un TextFrameEx. Lecture/écriture[`TextAnchorType`](../textanchortype) . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface IPresentationComponent de base. Lecture seule[`IPresentationComponent`](../ipresentationcomponent) . |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Renvoie ou définit le mode d'ajustement automatique du texte. Lecture/écriture[`TextAutofitType`](../textautofittype) . |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Si NullableBool.True, le texte doit être centré horizontalement dans la zone. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Renvoie ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera mise à zéro. La valeur 0 signifie une valeur indéfinie. Lecture/écritureInt32 . |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Renvoie ou définit l'espace entre les colonnes de texte dans la zone de texte (en points). Cela ne devrait s'appliquer que lorsqu'il y a plus d'une colonne présente. Cette valeur doit être un nombre positif. Sinon, la valeur sera mise à zéro. Lecture/écritureDouble . |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Obtient ou définit le maintien du texte plat même si un effet de rotation 3D a été appliqué. Lecture/écritureBoolean . |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Renvoie ou définit la marge inférieure (points) dans un TextFrame. Lecture/écritureDouble . |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Renvoie ou définit la marge gauche (points) dans un TextFrame. Lecture/écritureDouble . |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Renvoie ou définit la marge droite (points) dans un TextFrame. Lecture/écritureDouble . |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Renvoie ou définit la marge supérieure (points) dans un TextFrame. Lecture/écritureDouble . |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Spécifie la rotation personnalisée qui est appliquée au texte dans la zone de délimitation. S'il n'est pas spécifié , la rotation de la forme associée est utilisée. S'il est spécifié, alors ceci est appliqué indépendamment de la forme. C'est-à-dire que la forme peut avoir une rotation appliquée in en plus du texte lui-même auquel une rotation est appliquée. La valeur résultante de la rotation du texte visuel résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lecture/écritureSingle . |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Détermine l'orientation du texte. La valeur résultante de la rotation du texte visuel résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Lecture/écriture[`TextVerticalType`](../textverticaltype) . |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui représente les propriétés d'effet 3D pour un texte. Lecture seule[`IThreeDFormat`](../ithreedformat) . |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Obtient ou définit la forme d'habillage du texte. Lecture/écriture[`TextShapeType`](../textshapetype) . |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **Vrai** si le texte est enveloppé aux marges de TextFrame. Lecture/écriture[`NullableBool`](../nullablebool) . |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Obtient les données de formatage de cadre de texte efficaces avec l'héritage appliqué. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Voir également

* class [PVIObject](../pviobject)
* interface [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interface [ITextFrameFormat](../itextframeformat)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
