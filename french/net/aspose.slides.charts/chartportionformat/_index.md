---
title: ChartPortionFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Cette classe contient les propriétés de mise en forme des portions de graphique utilisées dans les graphiques. ContrairementIPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata  toutes les propriétés de cette classe sont accessibles en écriture.
type: docs
weight: 1310
url: /fr/net/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat class

Cette classe contient les propriétés de mise en forme des portions de graphique utilisées dans les graphiques. Contrairement[`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) , toutes les propriétés de cette classe sont accessibles en écriture.

```csharp
public class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Renvoie ou définit l'ID d'une autre langue. Lecture/écritureString . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface IPresentationComponent de base. Lecture seule[`IPresentationComponent`](../../aspose.slides/ipresentationcomponent) . |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Renvoie ou définit les informations sur la police du script complexe. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../../aspose.slides/ifontdata) . |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Renvoie ou définit les informations sur la police d'Asie de l'Est. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../../aspose.slides/ifontdata) . |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Renvoie les propriétés de texte EffectFormat. Aucun héritage appliqué. Lecture seule[`IEffectFormat`](../../aspose.slides/ieffectformat) . |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Renvoie ou définit le texte en exposant ou en indice. Valeur de -100 % (indice) à 100 % (exposant).  **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Renvoie les propriétés du texte FillFormat. Aucun héritage appliqué. Lecture seule[`IFillFormat`](../../aspose.slides/ifillformat) . |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../../aspose.slides/nullablebool) . |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Renvoie ou définit la hauteur de police d'une portion.  **float.NaN**signifie que la hauteur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Détermine si la police est en italique. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../../aspose.slides/nullablebool) . |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué. Lecture/écriture[`TextUnderlineType`](../../aspose.slides/textunderlinetype) . |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Renvoie la couleur utilisée pour surligner un texte. Aucun héritage appliqué. Lecture seule[`IColorFormat`](../../aspose.slides/icolorformat) . |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement a ses propres propriétés FillFormat ou hérite it des propriétés FillFormat du texte. Lecture/écriture[`NullableBool`](../../aspose.slides/nullablebool) . |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement a ses propres propriétés LineFormat ou hérite it des propriétés LineFormat du texte. Lecture/écriture[`NullableBool`](../../aspose.slides/nullablebool) . |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Renvoie ou définit la taille de police minimale pour laquelle le crénage doit être activé.  **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Détermine si les nombres doivent ignorer la disposition verticale du texte spécifique à la langue orientale. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../../aspose.slides/nullablebool) . |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Renvoie ou définit l'ID d'une langue de vérification. Utilisé pour vérifier l'orthographe et la grammaire. Lecture/écritureString . |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Renvoie ou définit les informations sur la police latine. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../../aspose.slides/ifontdata) . |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Renvoie les propriétés LineFormat pour le contour du texte. Aucun héritage appliqué. Lecture seule[`ILineFormat`](../../aspose.slides/ilineformat) . |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur d'un texte doit être normalisée. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../../aspose.slides/nullablebool) . |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être corrigé. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../../aspose.slides/nullablebool) . |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Renvoie ou définit l'incrément d'espacement entre les caractères.  **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Renvoie ou définit le type barré d'un texte. Aucun héritage appliqué. Lecture/écriture[`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Renvoie ou définit les informations sur la police symbolique. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../../aspose.slides/ifontdata) . |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué. Lecture/écriture[`TextCapType`](../../aspose.slides/textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Renvoie les propriétés FillFormat de la ligne de soulignement. Aucun héritage appliqué. Lecture seule[`IFillFormat`](../../aspose.slides/ifillformat) . |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Renvoie les propriétés LineFormat utilisées pour souligner la ligne de soulignement. Aucun héritage appliqué. Lecture seule[`ILineFormat`](../../aspose.slides/ilineformat) . |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés formatting de la portion de texte définies pour la portion particulière. Cela signifie que aucun héritage n'est appliqué lors de l'obtention de valeurs, donc pour la majorité des cas , vous obtiendrez des valeurs signifiant "indéfini".

Afin d'obtenir les valeurs de paramètre de mise en forme effectives incluant héritées, vous devez utiliser[`GetEffective`](../../aspose.slides/portionformat/geteffective) method qui renvoie un[`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) exemple.

### Voir également

* class [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->