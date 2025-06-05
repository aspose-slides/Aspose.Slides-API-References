---
title: PortionFormat
second_title: Aspose.Sildes pour .NET Référence API
description: Cette classe contient les propriétés de formatage de portion de texte. Contrairement à IPortionFormatEffectiveData, toutes les propriétés de cette classe sont écrites.
type: docs
weight: 9220
url: /fr/aspose.slides/portionformat/
---

## Classe PortionFormat

Cette classe contient les propriétés de formatage de portion de texte. Contrairement à [`IPortionFormatEffectiveData`](../iportionformateffectivedata), toutes les propriétés de cette classe sont écrites.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PortionFormat](portionformat)() | Initialise une nouvelle instance de la classe [`PortionFormat`](../portionformat). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retourne ou définit l'Id d'une langue alternative. Chaîne lisible/écrite. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Retourne ou définit l'identifiant de signet. Chaîne lisible/écrite. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retourne ou définit les informations sur la police de script complexe. Null signifie que la police est indéfinie et devrait être héritée du Maître. Lisible/écrite [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retourne ou définit les informations sur la police est-asiatique. Null signifie que la police est indéfinie et devrait être héritée du Maître. Lisible/écrite [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retourne les propriétés EffectFormat du texte. Pas d'héritage appliqué. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retourne ou définit le texte en exposant ou en indice. Valeur de -100 % (indice) à 100 % (exposant). **float.NaN** signifie que la valeur est indéfinie et devrait être héritée du Maître. Lisible/écrite Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retourne les propriétés FillFormat du texte. Pas d'héritage appliqué. Lecture seule [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Pas d'héritage appliqué. Lisible/écrite [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retourne ou définit la hauteur de la police d'une portion. **float.NaN** signifie que la hauteur est indéfinie et devrait être héritée du Maître. Lisible/écrite Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Détermine si la police est en italique. Pas d'héritage appliqué. Lisible/écrite [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retourne ou définit le type de soulignement du texte. Pas d'héritage appliqué. Lisible/écrite [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retourne la couleur utilisée pour mettre en surbrillance un texte. Pas d'héritage appliqué. Lecture seule [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Retourne ou définit l'hyperlien défini pour le clic de la souris. Lisible/écrite [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Gestionnaire d'hyperliens. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Retourne ou définit l'hyperlien défini pour le survol de la souris. Lisible/écrite [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement a ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lisible/écrite [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement a ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lisible/écrite [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retourne ou définit la taille de police minimale, pour laquelle le crénage doit être activé. **float.NaN** signifie que la valeur est indéfinie et devrait être héritée du Maître. Lisible/écrite Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Détermine si les nombres doivent ignorer la mise en page de texte vertical spécifique à la langue orientale. Pas d'héritage appliqué. Lisible/écrite [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retourne ou définit l'Id d'une langue de révision. Utilisé pour vérifier l'orthographe et la grammaire. Lisible/écrite String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retourne ou définit les informations sur la police latine. Null signifie que la police est indéfinie et devrait être héritée du Maître. Lisible/écrite [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retourne les propriétés LineFormat pour le contour des textes. Pas d'héritage appliqué. Lecture seule [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur d'un texte doit être normalisée. Pas d'héritage appliqué. Lisible/écrite [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être corrigé. Pas d'héritage appliqué. Lisible/écrite [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Détermine si la balise intelligente doit être nettoyée. Pas d'héritage appliqué. Lisible/écrite Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retourne ou définit l'incrément d'espacement intercaractères. **float.NaN** signifie que la valeur est indéfinie et devrait être héritée du Maître. Lisible/écrite Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retourne ou définit le type de barré d'un texte. Pas d'héritage appliqué. Lisible/écrite [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retourne ou définit les informations sur la police symbolique. Null signifie que la police est indéfinie et devrait être héritée du Maître. Lisible/écrite [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retourne ou définit le type de capitalisation du texte. Pas d'héritage appliqué. Lisible/écrite [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retourne les propriétés FillFormat de la ligne de soulignement. Pas d'héritage appliqué. Lecture seule [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retourne les propriétés LineFormat utilisées pour contourner la ligne de soulignement. Pas d'héritage appliqué. Lecture seule [`ILineFormat`](../ilineformat). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Obtient les données de formatage de portion effectives avec l'héritage appliqué. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourne le code de hachage. |

### Remarques

Cette classe est utilisée pour retourner et manipuler les propriétés de formatage de portion de texte définies pour la portion particulière. Cela signifie qu'aucun héritage n'est appliqué lors de l'obtention des valeurs, donc pour la majorité des cas, vous obtiendrez des valeurs signifiant "indéfini".

Pour obtenir les valeurs des paramètres de formatage effectifs, y compris celles héritées, vous devez utiliser la méthode [`GetEffective`](./geteffective) qui retourne une instance de [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Exemples

Les exemples suivants montrent comment attribuer la police latine à une portion de paragraphe d'une présentation PowerPoint.

```csharp
[C#]
//Instancier un objet présentation qui représente un fichier de présentation
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Format de texte de thème");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides utilise ces identifiants spéciaux (similaires à ceux utilisés dans PowerPoint):
// +mn-lt - Police de corps latin (Police mineure latine)
// +mj-lt - Police de titre latin (Police majeure latine)
// +mn-ea - Police de corps est-asiatique (Police mineure est-asiatique)
// +mj-ea - Police de corps est-asiatique (Police mineure est-asiatique)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Voir aussi

* classe [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->