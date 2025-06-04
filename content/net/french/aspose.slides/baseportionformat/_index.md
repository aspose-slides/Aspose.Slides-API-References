---
title: BasePortionFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Propriétés de formatage de portion de texte commun.
type: docs
weight: 890
url: /fr/aspose.slides/baseportionformat/
---

## Classe BasePortionFormat

Propriétés de formatage de portion de texte commun.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retourne ou définit l'Id d'une langue alternative. Lecture/écriture String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retourne ou définit les informations de police de script complexe. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retourne ou définit les informations de police est-asiatique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retourne les propriétés EffectFormat du texte. Pas d'héritage appliqué. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retourne ou définit le texte en exposant ou en indice. La valeur varie de -100 % (indice) à 100 % (exposant). **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retourne les propriétés FillFormat du texte. Pas d'héritage appliqué. Lecture seule [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Pas d'héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retourne ou définit la hauteur de la police d'une portion. **float.NaN** signifie que la hauteur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Détermine si la police est italique. Pas d'héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retourne ou définit le type de soulignement du texte. Pas d'héritage appliqué. Lecture/écriture [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retourne la couleur utilisée pour surligner un texte. Pas d'héritage appliqué. Lecture seule [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement a ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lecture/écriture [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement a ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lecture/écriture [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retourne ou définit la taille minimale de police, pour laquelle le crénage doit être activé. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Détermine si les nombres doivent ignorer la mise en page verticale spécifique aux langues orientales. Pas d'héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retourne ou définit l'Id d'une langue de correction. Utilisé pour vérifier l'orthographe et la grammaire. Lecture/écriture String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retourne ou définit les informations de police latine. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retourne les propriétés LineFormat pour le contour du texte. Pas d'héritage appliqué. Lecture seule [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur d'un texte doit être normalisée. Pas d'héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être corrigé. Pas d'héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retourne ou définit l'incrément d'espacement intercaractères. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retourne ou définit le type de barré d'un texte. Pas d'héritage appliqué. Lecture/écriture [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retourne ou définit les informations de police symbolique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retourne ou définit le type de capitalisation du texte. Pas d'héritage appliqué. Lecture/écriture [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retourne les propriétés FillFormat de la ligne de soulignement. Pas d'héritage appliqué. Lecture seule [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retourne les propriétés LineFormat utilisées pour contourner la ligne de soulignement. Pas d'héritage appliqué. Lecture seule [`ILineFormat`](../ilineformat). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourne le code de hachage. |

### Voir aussi

* classe [PVIObject](../pviobject)
* interface [IBasePortionFormat](../ibaseportionformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->