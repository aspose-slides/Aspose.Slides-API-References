---
title: IBasePortionFormatEffectiveData
second_title: Référence de l'API Aspose.Slides pour .NET
description: Interface de base pour les objets immuables qui contiennent des propriétés de formatage de portion de texte effectives.
type: docs
weight: 4870
url: /fr/net/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interface

Interface de base pour les objets immuables qui contiennent des propriétés de formatage de portion de texte effectives.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Renvoie l'ID d'une langue alternative. Lecture seuleString . |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Renvoie les informations sur la police de script complexe. Lecture seule[`IFontData`](../ifontdata) . |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Renvoie les informations sur la police d'Asie de l'Est. Lecture seule[`IFontData`](../ifontdata) . |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Renvoie les propriétés de texte EffectFormat. Lecture seule[`IEffectFormatEffectiveData`](../ieffectformateffectivedata) . |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Renvoie le texte en exposant ou en indice. Valeur de -100 % (indice) à 100 % (exposant). Lecture seuleSingle . |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Renvoie les propriétés du texte FillFormat. Lecture seule[`IFillFormatEffectiveData`](../ifillformateffectivedata) . |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Détermine si la police est en gras. Lecture seuleBoolean . |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Renvoie la hauteur de police d'une portion. Lecture seuleSingle . |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Détermine si la police est en italique. Lecture seuleBoolean . |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Renvoie le type de soulignement du texte. Lecture seule[`TextUnderlineType`](../textunderlinetype) . |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Renvoie la couleur utilisée pour surligner un texte. Lecture seuleColor . |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Détermine si le style de soulignement a ses propres propriétés FillFormat ou hérite it des propriétés FillFormat du texte. Lecture seuleBoolean . |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Détermine si le style de soulignement a ses propres propriétés LineFormat ou hérite it des propriétés LineFormat du texte. Lecture seuleBoolean . |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Renvoie la taille de police minimale pour laquelle le crénage doit être activé. Lecture seuleSingle . |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Détermine si les nombres doivent ignorer la disposition verticale du texte spécifique à la langue orientale. Lecture seuleBoolean . |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Renvoie l'ID d'une langue. Lecture seuleString . |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Renvoie les informations sur la police latine. Lecture seule[`IFontData`](../ifontdata) . |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Renvoie les propriétés LineFormat pour le contour du texte. Lecture seule[`ILineFormatEffectiveData`](../ilineformateffectivedata) . |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Détermine si la hauteur d'un texte doit être normalisée. Lecture seuleBoolean . |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Détermine si le texte ne doit pas être corrigé. Lecture seuleBoolean . |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Détermine si la balise active doit être nettoyée. Lecture seuleBoolean . |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Renvoie l'incrément d'espacement entre les caractères. Lecture seuleSingle . |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Renvoie le type barré d'un texte. Lecture seule[`TextStrikethroughType`](../textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Renvoie les informations sur la police symbolique. Lecture seule[`IFontData`](../ifontdata) . |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Renvoie le type de capitalisation du texte. Lecture seule[`TextCapType`](../textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Renvoie les propriétés FillFormat de la ligne de soulignement. Lecture seule[`IFillFormatEffectiveData`](../ifillformateffectivedata) . |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Renvoie les propriétés LineFormat utilisées pour souligner la ligne soulignée. Lecture seule[`ILineFormatEffectiveData`](../ilineformateffectivedata) . |

### Voir également

* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
