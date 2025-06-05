---
title: IBasePortionFormatEffectiveData
second_title: Référence API Aspose.Slides pour .NET
description: Interface de base pour des objets immuables qui contiennent des propriétés de formatage de portion de texte efficaces.
type: docs
weight: 5120
url: /fr/aspose.slides/ibaseportionformateffectivedata/
---

## Interface IBasePortionFormatEffectiveData

Interface de base pour des objets immuables qui contiennent des propriétés de formatage de portion de texte efficaces.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Renvoie l'Id d'une langue alternative. Chaîne en lecture seule. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Renvoie les informations sur la police de script complexe. Lire seule [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Renvoie les informations sur la police est-asiatique. Lire seule [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Renvoie les propriétés de format d'effet de texte. Lire seule [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Renvoie le texte en exposant ou en indice. Valeur de -100% (indice) à 100% (exposant). Lire seule Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Renvoie les propriétés de format de remplissage de texte. Lire seule [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Détermine si la police est en gras. Booléen en lecture seule. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Renvoie la hauteur de la police d'une portion. Lire seule Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Détermine si la police est en italique. Booléen en lecture seule. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Renvoie le type de soulignement du texte. Lire seule [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Renvoie la couleur utilisée pour mettre en surbrillance un texte. Couleur en lecture seule. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Détermine si le style de soulignement a ses propres propriétés de format de remplissage ou les hérite des propriétés de format de remplissage du texte. Booléen en lecture seule. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Détermine si le style de soulignement a ses propres propriétés de format de ligne ou les hérite des propriétés de format de ligne du texte. Booléen en lecture seule. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Renvoie la taille de police minimale, pour laquelle le crénage doit être activé. Lire seule Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Détermine si les chiffres doivent ignorer la disposition verticale spécifique aux langues orientales. Booléen en lecture seule. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Renvoie l'Id d'une langue. Chaîne en lecture seule. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Renvoie les informations sur la police latine. Lire seule [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Renvoie les propriétés de format de ligne pour le contour du texte. Lire seule [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Détermine si la hauteur d'un texte doit être normalisée. Booléen en lecture seule. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Détermine si le texte ne doit pas être relu. Booléen en lecture seule. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Détermine si la balise intelligente doit être nettoyée. Booléen en lecture seule. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Renvoie l'incrément d'espacement intercaractères. Lire seule Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Renvoie le type de barré d'un texte. Lire seule [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Renvoie les informations sur la police symbolique. Lire seule [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Renvoie le type de capitalisation du texte. Lire seule [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Renvoie les propriétés de format de remplissage de la ligne de soulignement. Lire seule [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Renvoie les propriétés de format de ligne utilisées pour contourer la ligne de soulignement. Lire seule [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Voir aussi

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->