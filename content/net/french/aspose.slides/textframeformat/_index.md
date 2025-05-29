---
title: TextFrameFormat
second_title: Aspose.Slides pour .NET Référence API
description: Contient les propriétés de formatage des TextFrames.
type: docs
weight: 10650
url: /fr/aspose.slides/textframeformat/
---

## Classe TextFrameFormat

Contient les propriétés de formatage des TextFrame.

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
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Retourne ou définit l'ancre verticale du texte dans un TextFrame. Lecture/écriture [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Retourne ou définit le mode d'ajustement automatique du texte. Lecture/écriture [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Si NullableBool.True, le texte doit être centré dans la boîte horizontalement. Lecture/écriture [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Retourne ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera définie sur zéro. La valeur 0 signifie valeur indéfinie. Lecture/écriture Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Retourne ou définit l'espace entre les colonnes de texte dans la zone de texte (en points). Cela ne doit s'appliquer que lorsqu'il y a plus d'une colonne présente. Cette valeur doit être un nombre positif. Sinon, la valeur sera définie sur zéro. Lecture/écriture Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Obtient ou définit le maintien du texte à plat même si un effet de rotation 3D a été appliqué. Lecture/écriture Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Retourne ou définit la marge inférieure (points) dans un TextFrame. Lecture/écriture Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Retourne ou définit la marge gauche (points) dans un TextFrame. Lecture/écriture Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Retourne ou définit la marge droite (points) dans un TextFrame. Lecture/écriture Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Retourne ou définit la marge supérieure (points) dans un TextFrame. Lecture/écriture Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Spécifie la rotation personnalisée appliquée au texte dans la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme accompagnante est utilisée. Si elle est spécifiée, alors cela est appliqué indépendamment de la forme. C'est-à-dire que la forme peut avoir une rotation appliquée en plus du texte lui-même ayant une rotation appliquée. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lecture/écriture Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Détermine l'orientation du texte. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Lecture/écriture [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Retourne l'objet ThreeDFormat qui représente les propriétés des effets 3D pour un texte. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Obtient ou définit la forme d'enroulement du texte. Lecture/écriture [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** si le texte est enroulé aux marges du TextFrame. Lecture/écriture [`NullableBool`](../nullablebool). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Obtient les données de formatage du cadre de texte effectif avec l'héritage appliqué. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourne le code de hachage. |

### Voir aussi

* classe [PVIObject](../pviobject)
* interface [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interface [ITextFrameFormat](../itextframeformat)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->