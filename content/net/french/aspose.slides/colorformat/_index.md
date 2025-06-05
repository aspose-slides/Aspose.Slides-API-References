---
title: ColorFormat
second_title: Référence API Aspose.Slides pour .NET
description: Représente une couleur utilisée dans une présentation.
type: docs
weight: 2430
url: /fr/aspose.slides/colorformat/
---

## ColorFormat class

Représente une couleur utilisée dans une présentation.

```csharp
public sealed class ColorFormat : PVIObject, IColorFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [B](../../aspose.slides/colorformat/b) { get; set; } | Renvoie ou définit le composant bleu d'une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture Byte. |
| [Color](../../aspose.slides/colorformat/color) { get; set; } | Renvoie la couleur résultante (avec toutes les transformations de couleur appliquées). Définit les couleurs RGB et efface toutes les transformations de couleur. Lecture/écriture Color. |
| [ColorTransform](../../aspose.slides/colorformat/colortransform) { get; } | Renvoie la collection des transformations de couleur appliquées à une couleur. Lecture seule [`IColorOperationCollection`](../icoloroperationcollection). |
| [ColorType](../../aspose.slides/colorformat/colortype) { get; set; } | Renvoie ou définit la méthode de définition de la couleur. Lecture/écriture [`ColorType`](../colortype). |
| [FloatB](../../aspose.slides/colorformat/floatb) { get; set; } | Renvoie ou définit le composant bleu d'une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture Single. |
| [FloatG](../../aspose.slides/colorformat/floatg) { get; set; } | Renvoie ou définit le composant vert d'une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture Single. |
| [FloatR](../../aspose.slides/colorformat/floatr) { get; set; } | Renvoie ou définit le composant rouge d'une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture Single. |
| [G](../../aspose.slides/colorformat/g) { get; set; } | Renvoie ou définit le composant vert d'une couleur. Toutes les transformations de couleur sont ignorées. |
| [Hue](../../aspose.slides/colorformat/hue) { get; set; } | Renvoie ou définit le composant teinte d'une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture Single. |
| [Luminance](../../aspose.slides/colorformat/luminance) { get; set; } | Renvoie ou définit le composant luminance d'une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture Single. |
| [PresetColor](../../aspose.slides/colorformat/presetcolor) { get; set; } | Renvoie ou définit le pré-réglage de couleur. Lecture/écriture [`PresetColor`](../presetcolor). |
| [R](../../aspose.slides/colorformat/r) { get; set; } | Renvoie ou définit le composant rouge d'une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture Byte. |
| [Saturation](../../aspose.slides/colorformat/saturation) { get; set; } | Renvoie ou définit le composant saturation d'une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture Single. |
| [SchemeColor](../../aspose.slides/colorformat/schemecolor) { get; set; } | Renvoie ou définit la couleur identifiée par un schéma de couleur. Lecture/écriture [`SchemeColor`](../schemecolor). |
| [SystemColor](../../aspose.slides/colorformat/systemcolor) { get; set; } | Renvoie ou définit la couleur identifiée par la table des couleurs système. Lecture/écriture [`SystemColor`](../systemcolor). |

## Methods

| Name | Description |
| --- | --- |
| [CopyFrom](../../aspose.slides/colorformat/copyfrom)(IColorFormat) | Copie le format de couleur de "color". |
| override [Equals](../../aspose.slides/colorformat/equals)(object) | Vérifie l'égalité avec l'objet spécifié. |
| override [GetHashCode](../../aspose.slides/colorformat/gethashcode)() | Renvoie le code de hachage. |
| [ToString](../../aspose.slides/colorformat/tostring#tostring_1)(ColorStringFormat) | Renvoie une chaîne qui représente le format de couleur actuel. |

### See Also

* class [PVIObject](../pviobject)
* interface [IColorFormat](../icolorformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)