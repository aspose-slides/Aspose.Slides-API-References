---
title: IBasePortionFormatEffectiveData
second_title: Référence de l'API Aspose.Slides pour .NET
description: Interface de base pour les objets immuables contenant des propriétés de formatage de portions de texte effectives.
type: docs
weight: 5120
url: /fr/aspose.slides/ibaseportionformateffectivedata/
---

## Interface IBasePortionFormatEffectiveData

Interface de base pour les objets immuables contenant des propriétés de formatage de portions de texte effectives.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Renvoie l'Id d'une langue alternative. Chaîne en lecture seule. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Renvoie les informations sur la police de script complexe. Chaîne en lecture seule [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Renvoie les informations sur la police est-asiatique. Chaîne en lecture seule [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Renvoie les propriétés EffectFormat du texte. Chaîne en lecture seule [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Renvoie le texte en exposant ou en indice. Valeur de -100 % (indice) à 100 % (exposant). Simple en lecture seule. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Renvoie les propriétés FillFormat du texte. Chaîne en lecture seule [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Détermine si la police est en gras. Booléen en lecture seule. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Renvoie la hauteur de la police d'une portion. Simple en lecture seule. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Détermine si la police est en italique. Booléen en lecture seule. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Renvoie le type de soulignement du texte. Chaîne en lecture seule [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Renvoie la couleur utilisée pour surligner un texte. Couleur en lecture seule. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Booléen en lecture seule. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Booléen en lecture seule. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Renvoie la taille minimale de police pour laquelle le crénage doit être activé. Simple en lecture seule. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Détermine si les chiffres doivent ignorer la mise en page verticale spécifique à la langue orientale. Booléen en lecture seule. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Renvoie l'Id d'une langue. Chaîne en lecture seule. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Renvoie les informations sur la police latine. Chaîne en lecture seule [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Renvoie les propriétés LineFormat pour le contour du texte. Chaîne en lecture seule [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Détermine si la hauteur d'un texte doit être normalisée. Booléen en lecture seule. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Détermine si le texte ne doit pas être relu. Booléen en lecture seule. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Détermine si la balise intelligente doit être nettoyée. Booléen en lecture seule. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Renvoie l'incrément d'espacement intercaractères. Simple en lecture seule. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Renvoie le type de barré d'un texte. Chaîne en lecture seule [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Renvoie les informations sur la police symbolique. Chaîne en lecture seule [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Renvoie le type de capitalisation du texte. Chaîne en lecture seule [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Renvoie les propriétés FillFormat de la ligne de soulignement. Chaîne en lecture seule [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Renvoie les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. Chaîne en lecture seule [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Voir aussi

* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->