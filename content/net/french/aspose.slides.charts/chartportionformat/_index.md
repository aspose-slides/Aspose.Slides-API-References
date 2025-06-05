---
title: ChartPortionFormat
second_title: Aspose.Slides pour .NET Référence API
description: Cette classe contient les propriétés de formatage de la portion de graphique utilisées dans les graphiques. Contrairement à IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 1350
url: /fr/aspose.slides.charts/chartportionformat/
---

## Classe ChartPortionFormat

Cette classe contient les propriétés de formatage de la portion de graphique utilisées dans les graphiques. Contrairement à [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retourne ou définit l'Id d'une langue alternative. Read/write String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Read-only [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retourne ou définit les informations sur la police de script complexe. Null signifie que la police est indéfinie et doit être héritée du Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retourne ou définit les informations sur la police d'Asie de l'Est. Null signifie que la police est indéfinie et doit être héritée du Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retourne les propriétés de format d'effet de texte. Pas d'héritage appliqué. Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retourne ou définit le texte en exposant ou en indice. Valeur de -100 % (indice) à 100 % (exposant). **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Read/write Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retourne les propriétés de format de remplissage de texte. Pas d'héritage appliqué. Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Pas d'héritage appliqué. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retourne ou définit la hauteur de la police d'une portion. **float.NaN** signifie que la hauteur est indéfinie et doit être héritée du Master. Read/write Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Détermine si la police est en italique. Pas d'héritage appliqué. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retourne ou définit le type de soulignement du texte. Pas d'héritage appliqué. Read/write [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retourne la couleur utilisée pour surligner un texte. Pas d'héritage appliqué. Read-only [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement a ses propres propriétés de FillFormat ou les hérite des propriétés de FillFormat du texte. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement a ses propres propriétés de LineFormat ou les hérite des propriétés de LineFormat du texte. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retourne ou définit la taille de police minimale pour laquelle le crénage doit être activé. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Read/write Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Détermine si les nombres doivent ignorer la disposition de texte verticale spécifique aux langues orientales. Pas d'héritage appliqué. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retourne ou définit l'Id d'une langue de vérification. Utilisé pour vérifier l'orthographe et la grammaire. Read/write String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retourne ou définit les informations sur la police latine. Null signifie que la police est indéfinie et doit être héritée du Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retourne les propriétés de LineFormat pour le contour du texte. Pas d'héritage appliqué. Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur d'un texte doit être normalisée. Pas d'héritage appliqué. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être vérifié. Pas d'héritage appliqué. Read/write [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retourne ou définit l'intervalle entre les caractères. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Read/write Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retourne ou définit le type de barré d'un texte. Pas d'héritage appliqué. Read/write [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retourne ou définit les informations sur la police symbolique. Null signifie que la police est indéfinie et doit être héritée du Master. Read/write [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retourne ou définit le type de capitalisation du texte. Pas d'héritage appliqué. Read/write [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retourne les propriétés de FillFormat de la ligne de soulignement. Pas d'héritage appliqué. Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retourne les propriétés de LineFormat utilisées pour le contour de la ligne de soulignement. Pas d'héritage appliqué. Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourne le code de hachage. |

### Remarques

Cette classe est utilisée pour retourner et manipuler les propriétés de formatage de portions de texte définies pour une portion particulière. Cela signifie qu'aucun héritage n'est appliqué lors de l'obtention des valeurs, donc dans la majorité des cas, vous obtiendrez des valeurs signifiant "indéfini".

Pour obtenir les valeurs des paramètres de formatage effectif, y compris les héritées, vous devez utiliser la méthode [`GetEffective`](../../aspose.slides/portionformat/geteffective) qui retourne une instance de [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Voir Aussi

* classe [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->