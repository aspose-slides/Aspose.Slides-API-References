---
title: BasePortionFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Propriétés communes de formatage des portions de texte.
type: docs
weight: 890
url: /fr/aspose.slides/baseportionformat/
---

## Classe BasePortionFormat

Propriétés communes de formatage des portions de texte.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retourne ou définit l'Id d'une langue alternative. Chaîne en lecture/écriture. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface IPresentationComponent de base. En lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retourne ou définit les informations de la police de script complexe. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retourne ou définit les informations de la police est-asiatique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retourne les propriétés EffectFormat du texte. Aucune héritage appliqué. En lecture seule [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retourne ou définit le texte en exposant ou en indice. La valeur va de -100 % (indice) à 100 % (exposant). **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Simple. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retourne les propriétés FillFormat du texte. Aucune héritage appliqué. En lecture seule [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Aucune héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retourne ou définit la hauteur de la police d'une portion. **float.NaN** signifie que la hauteur est indéfinie et doit être héritée du Master. Lecture/écriture Simple. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Détermine si la police est italique. Aucune héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retourne ou définit le type de soulignement du texte. Aucune héritage appliqué. Lecture/écriture [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retourne la couleur utilisée pour surligner un texte. Aucune héritage appliqué. En lecture seule [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement a ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lecture/écriture [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement a ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lecture/écriture [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retourne ou définit la taille de police minimale, pour laquelle le crénage doit être activé. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Simple. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Détermine si les chiffres doivent ignorer le formatage spécifique à la langue orientale du texte. Aucune héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retourne ou définit l'Id d'une langue de vérification. Utilisé pour vérifier l'orthographe et la grammaire. Lecture/écriture Chaîne. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retourne ou définit les informations de la police latine. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retourne les propriétés LineFormat pour le contour du texte. Aucune héritage appliqué. En lecture seule [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur d'un texte doit être normalisée. Aucune héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être vérifié. Aucune héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retourne ou définit l'augmentation de l'espacement intercaractères. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Simple. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retourne ou définit le type de barré d'un texte. Aucune héritage appliqué. Lecture/écriture [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retourne ou définit les informations de la police symbolique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retourne ou définit le type de capitalisation du texte. Aucune héritage appliqué. Lecture/écriture [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retourne les propriétés FillFormat de la ligne de soulignement. Aucune héritage appliqué. En lecture seule [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retourne les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. Aucune héritage appliqué. En lecture seule [`ILineFormat`](../ilineformat). |

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