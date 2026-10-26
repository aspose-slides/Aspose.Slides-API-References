---
title: TextFrameFormat
second_title: Aspose.Sildes pour .NET Référence de l'API
description: Contient les propriétés formatTextFrameFormatting des TextFrames.
type: docs
weight: 10960
url: /fr/aspose.slides/textframeformat/
---
## TextFrameFormat classe

Contient les propriétés formatTextFrameFormatting du TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Initialise une nouvelle instance de la classe [`TextFrameFormat`](../textframeformat). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Renvoie ou définit le texte d'ancrage vertical dans un TextFrame. Lecture/écriture [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Renvoie ou définit le mode d'ajustement automatique du texte. Lecture/écriture [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. Lecture/écriture [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Renvoie ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera définie sur zéro. La valeur 0 signifie valeur indéfinie. Lecture/écriture Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Renvoie ou définit l'espace entre les colonnes de texte dans la zone de texte (en points). Ceci ne s'applique que lorsqu'il y a plus d'une colonne. Cette valeur doit être un nombre positif. Sinon, la valeur sera définie sur zéro. Lecture/écriture Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Obtient ou définit le maintien du texte à plat même si un effet de rotation 3-D a été appliqué. Lecture/écriture Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Renvoie ou définit la marge inférieure (points) d'un TextFrame. Lecture/écriture Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Renvoie ou définit la marge gauche (points) d'un TextFrame. Lecture/écriture Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Renvoie ou définit la marge droite (points) d'un TextFrame. Lecture/écriture Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Renvoie ou définit la marge supérieure (points) d'un TextFrame. Lecture/écriture Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation du texte lui-même. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lecture/écriture Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Détermine l'orientation du texte. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Lecture/écriture [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui représente les propriétés d'effet 3D pour un texte. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Obtient ou définit la forme d'habillage du texte. Lecture/écriture [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** si le texte est enveloppé aux marges du TextFrame. Lecture/écriture [`NullableBool`](../nullablebool). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Obtient les données de formatage effectif du cadre de texte avec l'héritage appliqué. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Voir aussi

* classe [PVIObject](../pviobject)
* interface [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interface [ITextFrameFormat](../itextframeformat)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->