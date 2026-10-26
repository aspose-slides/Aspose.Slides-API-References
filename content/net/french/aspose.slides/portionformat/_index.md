---
title: PortionFormat
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Cette classe contient les propriétés de formatage des portions de texte. Contrairement à IPortionFormatEffectiveData./iportionformateffectivedata, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 9490
url: /fr/aspose.slides/portionformat/
---
## PortionFormat classe

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
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Renvoie ou définit l'Id d'une langue alternative. Lecture/écriture String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Renvoie ou définit l'identifiant du signet. Lecture/écriture String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Renvoie ou définit les informations de police de script complexe. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Renvoie ou définit les informations de police Est-Asiatique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Renvoie les propriétés EffectFormat du texte. Aucun héritage appliqué. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Renvoie ou définit le texte en exposant ou en indice. Valeur de -100 % (indice) à 100 % (exposant). **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Renvoie les propriétés FillFormat du texte. Aucun héritage appliqué. Lecture seule [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Renvoie ou définit la hauteur de police d'une portion. **float.NaN** signifie que la hauteur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Détermine si la police est italique. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué. Lecture/écriture [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Renvoie la couleur utilisée pour mettre en surbrillance un texte. Aucun héritage appliqué. Lecture seule [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Gestionnaire de liens hypertexte. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lecture/écriture [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lecture/écriture [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Renvoie ou définit la taille minimale de police pour laquelle le crénage doit être activé. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Détermine si les chiffres doivent ignorer la mise en page verticale spécifique aux langues orientales du texte. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Renvoie ou définit l'Id d'une langue de correction. Utilisée pour la vérification d'orthographe et de grammaire. Lecture/écriture String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Renvoie ou définit les informations de police Latin. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Renvoie les propriétés LineFormat pour le contour du texte. Aucun héritage appliqué. Lecture seule [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur du texte doit être normalisée. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être corrigé. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Détermine si la smart tag doit être nettoyée. Aucun héritage appliqué. Lecture/écriture Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Renvoie ou définit l'incrément d'espacement inter-caractères. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Obtient ou définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications d'orthographe des éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. Valeur par défaut : `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Renvoie ou définit le type de barré du texte. Aucun héritage appliqué. Lecture/écriture [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Renvoie ou définit les informations de police symbolique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué. Lecture/écriture [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Renvoie les propriétés FillFormat de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Renvoie les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [`ILineFormat`](../ilineformat). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Obtient les données de formatage de portion effectives avec l'héritage appliqué. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage de portion de texte définies pour la portion particulière. Cela signifie qu'aucun héritage n'est appliqué lors de la récupération des valeurs, de sorte que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de formatage, y compris ceux hérités, vous devez utiliser la méthode [`GetEffective`](./geteffective) qui renvoie une instance [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Exemples

L'exemple suivant montre comment assigner la police Latin à une portion de paragraphe d'une présentation PowerPoint.

```csharp
[C#]
//Instanciez un objet présentation qui représente un fichier de présentation
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides utilise ces identifiants spéciaux (similaires à ceux utilisés dans PowerPoint) :
// +mn-lt - Police du corps Latin (Police Latin mineure)
// +mj-lt -Police du titre Latin (Police Latin majeure)
// +mn-ea - Police du corps Asie de l'Est (Police Asie de l'Est mineure)
// +mj-ea - Police du corps Asie de l'Est (Police Asie de l'Est mineure)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Voir aussi

* classe [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->