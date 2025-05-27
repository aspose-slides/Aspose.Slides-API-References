---
title: PortionFormat
second_title: Aspose.Slides pour la référence de l'API .NET
description: Cette classe contient les propriétés de formatage des portions de texte. Contrairement à IPortionFormatEffectiveData../iportionformateffectivedata, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 9220
url: /fr/aspose.slides/portionformat/
---

## Classe PortionFormat

Cette classe contient les propriétés de formatage des portions de texte. Contrairement à [`IPortionFormatEffectiveData`](../iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

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
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Renvoie ou définit l'Id d'une langue alternative. Chaîne en lecture/écriture. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. En lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Renvoie ou définit l'identifiant du signet. Chaîne en lecture/écriture. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Renvoie ou définit les informations sur la police de script complexe. Null signifie que la police est indéfinie et doit être héritée du Maître. En lecture/écriture [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Renvoie ou définit les informations sur la police est-asiatique. Null signifie que la police est indéfinie et doit être héritée du Maître. En lecture/écriture [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Renvoie les propriétés de type EffectFormat pour le texte. Pas d'héritage appliqué. En lecture seule [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Renvoie ou définit le texte en exposant ou en indice. Valeur de -100 % (indice) à 100 % (exposant). **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Maître. En lecture/écriture Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Renvoie les propriétés de type FillFormat pour le texte. Pas d'héritage appliqué. En lecture seule [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Pas d'héritage appliqué. En lecture/écriture [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Renvoie ou définit la hauteur de la police d'une portion. **float.NaN** signifie que la hauteur est indéfinie et doit être héritée du Maître. En lecture/écriture Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Détermine si la police est en italique. Pas d'héritage appliqué. En lecture/écriture [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Renvoie ou définit le type de soulignement du texte. Pas d'héritage appliqué. En lecture/écriture [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Renvoie la couleur utilisée pour surligner un texte. Pas d'héritage appliqué. En lecture seule [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Renvoie ou définit l'hyperlien défini pour le clic de souris. En lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Gestionnaire d'hyperliens. En lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Renvoie ou définit l'hyperlien défini pour le survol de la souris. En lecture/écriture [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement a ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. En lecture/écriture [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement a ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. En lecture/écriture [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Renvoie ou définit la taille minimale de police, pour laquelle le crénage doit être activé. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Maître. En lecture/écriture Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Détermine si les chiffres doivent ignorer la mise en page verticale spécifique aux langues orientales. Pas d'héritage appliqué. En lecture/écriture [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Renvoie ou définit l'Id d'une langue de correction. Utilisé pour vérifier l'orthographe et la grammaire. Chaîne en lecture/écriture. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Renvoie ou définit les informations sur la police latine. Null signifie que la police est indéfinie et doit être héritée du Maître. En lecture/écriture [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Renvoie les propriétés LineFormat pour le contour du texte. Pas d'héritage appliqué. En lecture seule [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur d'un texte doit être normalisée. Pas d'héritage appliqué. En lecture/écriture [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être corrigé. Pas d'héritage appliqué. En lecture/écriture [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Détermine si la balise intelligente doit être nettoyée. Pas d'héritage appliqué. En lecture/écriture Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Renvoie ou définit l'intervalle d'espacement intercaractères. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Maître. En lecture/écriture Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Renvoie ou définit le type de barré d'un texte. Pas d'héritage appliqué. En lecture/écriture [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Renvoie ou définit les informations sur la police symbolique. Null signifie que la police est indéfinie et doit être héritée du Maître. En lecture/écriture [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Renvoie ou définit le type de capitalisation du texte. Pas d'héritage appliqué. En lecture/écriture [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Renvoie les propriétés de type FillFormat pour la ligne de soulignement. Pas d'héritage appliqué. En lecture seule [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Renvoie les propriétés LineFormat utilisées pour contourner la ligne de soulignement. Pas d'héritage appliqué. En lecture seule [`ILineFormat`](../ilineformat). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Obtient les données de formatage de portion effectives avec l'héritage appliqué. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Remarques

Cette classe est utilisée pour retourner et manipuler les propriétés de formatage des portions de texte définies pour la portion particulière. Cela signifie qu'aucun héritage n'est appliqué lors de l'obtention des valeurs, donc dans la majorité des cas, vous obtiendrez des valeurs signifiant "indéfini".

Pour obtenir les valeurs des paramètres de formatage effectif, y compris héritées, vous devez utiliser la méthode [`GetEffective`](./geteffective) qui renvoie une instance de [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Exemples

Les exemples suivants montrent comment assigner la police latine à la portion d'un paragraphe d'une présentation PowerPoint.

```csharp
[C#]
//Instancier un objet de présentation qui représente un fichier de présentation
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Format de texte thématique");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides utilise ces identifiants spéciaux (similaires à ceux utilisés dans PowerPoint):
// +mn-lt - Police de corps latine (Police latine mineure)
// +mj-lt - Police de titre latine (Police latine majeure)
// +mn-ea - Police de corps est-asiatique (Police est-asiatique mineure)
// +mj-ea - Police de titre est-asiatique (Police est-asiatique majeure)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Voir aussi

* classe [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)