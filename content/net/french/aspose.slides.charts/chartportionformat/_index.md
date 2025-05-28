---
title: ChartPortionFormat
second_title: Référence API Aspose.Slides pour .NET
description: Cette classe contient les propriétés de formatage de portion de graphique utilisées dans les graphiques. Contrairement à IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 1350
url: /fr/aspose.slides.charts/chartportionformat/
---

## Classe ChartPortionFormat

Cette classe contient les propriétés de formatage de portion de graphique utilisées dans les graphiques. Contrairement à [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Renvoie ou définit l'ID d'une langue alternative. Chaîne lisible/écrivable. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Renvoie ou définit les informations sur la police de script complexe. Null signifie que la police n'est pas définie et doit être héritée du Maître. Lisible/écrivable [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Renvoie ou définit les informations sur la police d'Asie de l'Est. Null signifie que la police n'est pas définie et doit être héritée du Maître. Lisible/écrivable [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Renvoie les propriétés de l'EffectFormat du texte. Aucun héritage appliqué. Lecture seule [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Renvoie ou définit le texte en exposant ou en indice. Valeur de -100 % (indice) à 100 % (exposant). **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du Maître. Lisible/écrivable Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Renvoie les propriétés de l'FillFormat du texte. Aucun héritage appliqué. Lecture seule [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Aucun héritage appliqué. Lisible/écrivable [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Renvoie ou définit la hauteur de la police d'une portion. **float.NaN** signifie que la hauteur n'est pas définie et doit être héritée du Maître. Lisible/écrivable Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Détermine si la police est en italique. Aucun héritage appliqué. Lisible/écrivable [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué. Lisible/écrivable [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Renvoie la couleur utilisée pour surligner un texte. Aucun héritage appliqué. Lecture seule [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement a ses propres propriétés de FillFormat ou les hérite des propriétés de FillFormat du texte. Lisible/écrivable [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement a ses propres propriétés de LineFormat ou les hérite des propriétés de LineFormat du texte. Lisible/écrivable [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Renvoie ou définit la taille minimale de police, pour laquelle le crénage doit être activé. **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du Maître. Lisible/écrivable Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Détermine si les chiffres doivent ignorer la mise en page de texte vertical spécifique aux langues orientales. Aucun héritage appliqué. Lisible/écrivable [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Renvoie ou définit l'ID d'une langue de révision. Utilisé pour vérifier l'orthographe et la grammaire. Lisible/écrivable String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Renvoie ou définit les informations sur la police latine. Null signifie que la police n'est pas définie et doit être héritée du Maître. Lisible/écrivable [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Renvoie les propriétés de LineFormat pour l'outreling de texte. Aucun héritage appliqué. Lecture seule [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur d'un texte doit être normalisée. Aucun héritage appliqué. Lisible/écrivable [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être révisé. Aucun héritage appliqué. Lisible/écrivable [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Renvoie ou définit l'incrément d'espacement entre les caractères. **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du Maître. Lisible/écrivable Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Renvoie ou définit le type de barré d'un texte. Aucun héritage appliqué. Lisible/écrivable [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Renvoie ou définit les informations sur la police symbolique. Null signifie que la police n'est pas définie et doit être héritée du Maître. Lisible/écrivable [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué. Lisible/écrivable [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Renvoie les propriétés de FillFormat de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Renvoie les propriétés de LineFormat utilisées pour décrire la ligne de soulignement. Aucun héritage appliqué. Lecture seule [`ILineFormat`](../../aspose.slides/ilineformat). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare l'objet spécifié. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage de portion de texte définies pour la portion particulière. Cela signifie qu'aucun héritage n'est appliqué lors de la récupération des valeurs, donc dans la majorité des cas, vous obtiendrez des valeurs signifiant "indéfini".

Pour obtenir les valeurs des paramètres de formatage effectif, y compris celles héritées, vous devez utiliser la méthode [`GetEffective`](../../aspose.slides/portionformat/geteffective) qui renvoie une instance de [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Voir aussi

* classe [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->