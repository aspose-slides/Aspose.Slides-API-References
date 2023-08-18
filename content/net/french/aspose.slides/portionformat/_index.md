---
title: PortionFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Cette classe contient les propriétés de formatage des portions de texte. Contrairement àIPortionFormatEffectiveData./iportionformateffectivedata  toutes les propriétés de cette classe sont accessibles en écriture.
type: docs
weight: 8790
url: /fr/aspose.slides/portionformat/
---
## PortionFormat class

Cette classe contient les propriétés de formatage des portions de texte. Contrairement à[`IPortionFormatEffectiveData`](../iportionformateffectivedata) , toutes les propriétés de cette classe sont accessibles en écriture.

```csharp
public class PortionFormat : BasePortionFormat, IPortionFormat
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PortionFormat](portionformat)() | Initialise une nouvelle instance de[`PortionFormat`](../portionformat) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Renvoie ou définit l'ID d'une autre langue. Lecture/écritureString . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface IPresentationComponent de base. Lecture seule[`IPresentationComponent`](../ipresentationcomponent) . |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Renvoie ou définit l'identifiant du signet. Lecture/écritureString . |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Renvoie ou définit les informations sur la police du script complexe. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../ifontdata) . |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Renvoie ou définit les informations sur la police d'Asie de l'Est. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../ifontdata) . |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Renvoie les propriétés de texte EffectFormat. Aucun héritage appliqué. Lecture seule[`IEffectFormat`](../ieffectformat) . |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Renvoie ou définit le texte en exposant ou en indice. Valeur de -100 % (indice) à 100 % (exposant).  **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Renvoie les propriétés du texte FillFormat. Aucun héritage appliqué. Lecture seule[`IFillFormat`](../ifillformat) . |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Renvoie ou définit la hauteur de police d'une portion.  **float.NaN**signifie que la hauteur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Détermine si la police est en italique. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué. Lecture/écriture[`TextUnderlineType`](../textunderlinetype) . |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Renvoie la couleur utilisée pour surligner un texte. Aucun héritage appliqué. Lecture seule[`IColorFormat`](../icolorformat) . |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Gestionnaire d'hyperliens. Lecture seule[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture[`IHyperlink`](../ihyperlink) . |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement a ses propres propriétés FillFormat ou hérite it des propriétés FillFormat du texte. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement a ses propres propriétés LineFormat ou hérite it des propriétés LineFormat du texte. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Renvoie ou définit la taille de police minimale pour laquelle le crénage doit être activé.  **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Détermine si les nombres doivent ignorer la disposition verticale du texte spécifique à la langue orientale. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Renvoie ou définit l'ID d'une langue de vérification. Utilisé pour vérifier l'orthographe et la grammaire. Lecture/écritureString . |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Renvoie ou définit les informations sur la police latine. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../ifontdata) . |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Renvoie les propriétés LineFormat pour le contour du texte. Aucun héritage appliqué. Lecture seule[`ILineFormat`](../ilineformat) . |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur d'un texte doit être normalisée. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être corrigé. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Détermine si la balise active doit être nettoyée. Aucun héritage appliqué. Lecture/écritureBoolean . |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Renvoie ou définit l'incrément d'espacement entre les caractères.  **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Renvoie ou définit le type barré d'un texte. Aucun héritage appliqué. Lecture/écriture[`TextStrikethroughType`](../textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Renvoie ou définit les informations sur la police symbolique. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../ifontdata) . |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué. Lecture/écriture[`TextCapType`](../textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Renvoie les propriétés FillFormat de la ligne de soulignement. Aucun héritage appliqué. Lecture seule[`IFillFormat`](../ifillformat) . |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Renvoie les propriétés LineFormat utilisées pour souligner la ligne de soulignement. Aucun héritage appliqué. Lecture seule[`ILineFormat`](../ilineformat) . |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Obtient les données de mise en forme des portions effectives avec l'héritage appliqué. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage de la portion de texte définies pour la portion particulière. Cela signifie que aucun héritage n'est appliqué lors de l'obtention de valeurs, donc dans la majorité des cas, vous obtiendrez des valeurs signifiant "indéfini".

Afin d'obtenir les valeurs de paramètre de formatage efficaces, y compris héritées, vous devez utiliser[`GetEffective`](./geteffective) méthode qui renvoie un[`IPortionFormatEffectiveData`](../iportionformateffectivedata) exemple.

### Voir également

* class [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
