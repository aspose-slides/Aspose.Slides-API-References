---
title: ITextFrameFormat
second_title: Aspose.Sildes pour .NET API Reference
description: Contient les propriétés de formatage des TextFrames.
type: docs
weight: 7060
url: /fr/aspose.slides/itextframeformat/
---

## Interface ITextFrameFormat

Contient les propriétés de formatage du TextFrame.

```csharp
public interface ITextFrameFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AnchoringType](../../aspose.slides/itextframeformat/anchoringtype) { get; set; } | Retourne ou définit l'ancre verticale du texte dans un TextFrame. Lecture/écriture [`TextAnchorType`](../textanchortype). |
| [AutofitType](../../aspose.slides/itextframeformat/autofittype) { get; set; } | Retourne ou définit le mode d'ajustement automatique du texte. Lecture/écriture [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/itextframeformat/centertext) { get; set; } | Si NullableBool.True, le texte doit être centré dans la boîte horizontalement. Lecture/écriture [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/itextframeformat/columncount) { get; set; } | Retourne ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera fixée à zéro. La valeur 0 signifie valeur indéfinie. Lecture/écriture Int32. |
| [ColumnSpacing](../../aspose.slides/itextframeformat/columnspacing) { get; set; } | Retourne ou définit l'espace entre les colonnes de texte dans la zone de texte (en points). Cela ne devrait s'appliquer que lorsqu'il y a plus d'une colonne présente. Cette valeur doit être un nombre positif. Sinon, la valeur sera fixée à zéro. Lecture/écriture Double. |
| [KeepTextFlat](../../aspose.slides/itextframeformat/keeptextflat) { get; set; } | Retourne ou définit le maintien du texte complètement en dehors de la scène 3D. Lecture/écriture Boolean. |
| [MarginBottom](../../aspose.slides/itextframeformat/marginbottom) { get; set; } | Retourne ou définit la marge inférieure (points) dans un TextFrame. Lecture/écriture Double. |
| [MarginLeft](../../aspose.slides/itextframeformat/marginleft) { get; set; } | Retourne ou définit la marge gauche (points) dans un TextFrame. Lecture/écriture Double. |
| [MarginRight](../../aspose.slides/itextframeformat/marginright) { get; set; } | Retourne ou définit la marge droite (points) dans un TextFrame. Lecture/écriture Double. |
| [MarginTop](../../aspose.slides/itextframeformat/margintop) { get; set; } | Retourne ou définit la marge supérieure (points) dans un TextFrame. Lecture/écriture Double. |
| [RotationAngle](../../aspose.slides/itextframeformat/rotationangle) { get; set; } | Spécifie la rotation personnalisée qui est appliquée au texte à l'intérieur de la zone de délimitation. Si elle n'est pas spécifiée, la rotation de la forme accompagnante est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. C'est-à-dire que la forme peut avoir une rotation appliquée en plus du texte lui-même ayant une rotation appliquée. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lecture/écriture Single. |
| [TextStyle](../../aspose.slides/itextframeformat/textstyle) { get; } | Retourne le style du texte. Lecture seule [`ITextStyle`](../itextstyle). |
| [TextVerticalType](../../aspose.slides/itextframeformat/textverticaltype) { get; set; } | Détermine l'orientation du texte. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Lecture/écriture [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/itextframeformat/threedformat) { get; } | Retourne l'objet ThreeDFormat qui représente les propriétés d'effet 3D pour un texte. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/itextframeformat/transform) { get; set; } | Obtient ou définit la forme d'enroulement du texte. Lecture/écriture [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/itextframeformat/wraptext) { get; set; } | **True** si le texte est enveloppé aux marges du TextFrame. Lecture/écriture [`NullableBool`](../nullablebool). |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetEffective](../../aspose.slides/itextframeformat/geteffective)() | Obtient les données de formatage du cadre de texte effectif avec l'héritage appliqué. |

### Voir aussi

* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->