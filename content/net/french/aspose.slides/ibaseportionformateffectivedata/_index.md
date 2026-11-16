---
title: IBasePortionFormatEffectiveData
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Interface de base pour les objets immuables contenant les propriétés de formatage effectif des portions de texte.
type: docs
weight: 5340
url: /fr/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interface

Interface de base pour les objets immuables contenant les propriétés de formatage effectif des portions de texte.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Renvoie l'Id d'une langue alternative. Lecture seule String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Renvoie les informations de police de script complexe. Lecture seule [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Renvoie les informations de police d'Asie de l'Est. Lecture seule [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Renvoie les propriétés EffectFormat du texte. Lecture seule [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Renvoie le texte en exposant ou indice. Valeur de -100% (indice) à 100% (exposant). Lecture seule Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Renvoie les propriétés FillFormat du texte. Lecture seule [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Détermine si la police est en gras. Lecture seule Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Renvoie la hauteur de police de la portion de texte, en points. Lecture seule Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Détermine si la police est italique. Lecture seule Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Renvoie le type de soulignement du texte. Lecture seule [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Renvoie la couleur utilisée pour mettre en évidence un texte. Lecture seule Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lecture seule Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Détermine si le style de soulinement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lecture seule Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Renvoie la taille de police minimale pour laquelle le crénage doit être activé. Lecture seule Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Détermine si les chiffres doivent ignorer la disposition verticale du texte propre aux langues orientales. Lecture seule Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Renvoie l'Id d'une langue. Lecture seule String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Renvoie les informations de police Latin. Lecture seule [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Renvoie les propriétés LineFormat pour le contour du texte. Lecture seule [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Détermine si la hauteur d'un texte doit être normalisée. Lecture seule Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Détermine si le texte ne doit pas être vérifié. Lecture seule Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Détermine si la balise intelligente doit être nettoyée. Lecture seule Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Renvoie l'incrément d'espacement inter-caractères, en points. Lecture seule Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Renvoie le type de barré d'un texte. Lecture seule [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Renvoie les informations de police symbolique. Lecture seule [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Renvoie le type de capitalisation du texte. Lecture seule [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Renvoie les propriétés FillFormat de la ligne de soulignement. Lecture seule [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Renvoie les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. Lecture seule [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Voir aussi

* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->