---
title: IBasePortionFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Cette classe contient les propriétés de formatage de la portion de texte. Contrairement à IPortionFormatEffectiveData, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 5110
url: /fr/aspose.slides/ibaseportionformat/
---

## Interface IBasePortionFormat

Cette classe contient les propriétés de formatage de la portion de texte. Contrairement à [`IPortionFormatEffectiveData`](../iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

```csharp
public interface IBasePortionFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Renvoie ou définit l'Id d'une langue alternative. Lecture/écriture String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Renvoie ou définit les informations de police pour le script complexe. Null signifie que la police n'est pas définie et doit être héritée du Maître. Lecture/écriture [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Renvoie ou définit les informations de police pour l'Asie de l'Est. Null signifie que la police n'est pas définie et doit être héritée du Maître. Lecture/écriture [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Renvoie les propriétés EffectFormat du texte. Pas d'héritage appliqué. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Renvoie ou définit le texte en exposant ou en indice. Valeur de -100% (indice) à 100% (exposant). **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du Maître. Lecture/écriture Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Renvoie les propriétés FillFormat du texte. Pas d'héritage appliqué. Lecture seule [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Pas d'héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Renvoie ou définit la hauteur de police d'une portion. **float.NaN** signifie que la hauteur n'est pas définie et doit être héritée du Maître. Lecture/écriture Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Détermine si la police est en italique. Pas d'héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Renvoie ou définit le type de soulignement du texte. Pas d'héritage appliqué. Lecture/écriture [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Renvoie la couleur utilisée pour surligner un texte. Pas d'héritage appliqué. Lecture seule [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement a ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lecture/écriture [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement a ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lecture/écriture [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Renvoie ou définit la taille de police minimale, pour laquelle le crénage doit être activé. **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du Maître. Lecture/écriture Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Détermine si les chiffres doivent ignorer l'agencement vertical spécifique aux langues orientales. Pas d'héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Renvoie ou définit l'Id d'une langue de vérification. Utilisé pour vérifier l'orthographe et la grammaire. Lecture/écriture String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Renvoie ou définit les informations de police latine. Null signifie que la police n'est pas définie et doit être héritée du Maître. Lecture/écriture [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Renvoie les propriétés LineFormat pour le contour du texte. Pas d'héritage appliqué. Lecture seule [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur d'un texte doit être normalisée. Pas d'héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être relu. Pas d'héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Renvoie ou définit l'augmentation de l'espacement intercaractères. **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du Maître. Lecture/écriture Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Renvoie ou définit le type de barré d'un texte. Pas d'héritage appliqué. Lecture/écriture [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Renvoie ou définit les informations de police symbolique. Null signifie que la police n'est pas définie et doit être héritée du Maître. Lecture/écriture [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Renvoie ou définit le type de capitalisation du texte. Pas d'héritage appliqué. Lecture/écriture [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Renvoie les propriétés FillFormat de la ligne de soulignement. Pas d'héritage appliqué. Lecture seule [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Renvoie les propriétés LineFormat utilisées pour contourer la ligne de soulignement. Pas d'héritage appliqué. Lecture seule [`ILineFormat`](../ilineformat). |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage de la portion de texte définies pour la portion particulière. Cela signifie qu'aucun héritage n'est appliqué lors de l'obtention des valeurs, donc dans la majorité des cas, vous obtiendrez des valeurs signifiant "non défini".

Afin d'obtenir les valeurs des paramètres de formatage effectif, y compris l'héritage, vous devez utiliser la méthode [`GetEffective`](../iportionformat/geteffective) qui renvoie une instance de [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Voir aussi

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->