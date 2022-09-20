---
title: IBasePortionFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Cette classe contient les propriétés de formatage des portions de texte. Contrairement àIPortionFormatEffectiveData./iportionformateffectivedata  toutes les propriétés de cette classe sont accessibles en écriture.
type: docs
weight: 4860
url: /fr/net/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interface

Cette classe contient les propriétés de formatage des portions de texte. Contrairement à[`IPortionFormatEffectiveData`](../iportionformateffectivedata) , toutes les propriétés de cette classe sont accessibles en écriture.

```csharp
public interface IBasePortionFormat
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Renvoie ou définit l'ID d'une autre langue. Lecture/écritureString . |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Renvoie ou définit les informations sur la police du script complexe. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../ifontdata) . |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Renvoie ou définit les informations sur la police d'Asie de l'Est. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../ifontdata) . |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Renvoie les propriétés de texte EffectFormat. Aucun héritage appliqué. Lecture seule[`IEffectFormat`](../ieffectformat) . |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Renvoie ou définit le texte en exposant ou en indice. Valeur de -100 % (indice) à 100 % (exposant).  **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Renvoie les propriétés du texte FillFormat. Aucun héritage appliqué. Lecture seule[`IFillFormat`](../ifillformat) . |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Renvoie ou définit la hauteur de police d'une portion.  **float.NaN**signifie que la hauteur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Détermine si la police est en italique. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué. Lecture/écriture[`TextUnderlineType`](../textunderlinetype) . |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Renvoie la couleur utilisée pour surligner un texte. Aucun héritage appliqué. Lecture seule[`IColorFormat`](../icolorformat) . |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement a ses propres propriétés FillFormat ou hérite it des propriétés FillFormat du texte. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement a ses propres propriétés LineFormat ou hérite it des propriétés LineFormat du texte. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Renvoie ou définit la taille de police minimale pour laquelle le crénage doit être activé.  **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Détermine si les nombres doivent ignorer la disposition verticale du texte spécifique à la langue orientale. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Renvoie ou définit l'ID d'une langue de vérification. Utilisé pour vérifier l'orthographe et la grammaire. Lecture/écritureString . |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Renvoie ou définit les informations sur la police latine. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../ifontdata) . |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Renvoie les propriétés LineFormat pour le contour du texte. Aucun héritage appliqué. Lecture seule[`ILineFormat`](../ilineformat) . |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur d'un texte doit être normalisée. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être corrigé. Aucun héritage appliqué. Lecture/écriture[`NullableBool`](../nullablebool) . |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Renvoie ou définit l'incrément d'espacement entre les caractères.  **float.NaN** signifie que la valeur n'est pas définie et doit être héritée du maître. Lecture/écritureSingle . |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Renvoie ou définit le type barré d'un texte. Aucun héritage appliqué. Lecture/écriture[`TextStrikethroughType`](../textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Renvoie ou définit les informations sur la police symbolique. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture/écriture[`IFontData`](../ifontdata) . |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué. Lecture/écriture[`TextCapType`](../textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Renvoie les propriétés FillFormat de la ligne de soulignement. Aucun héritage appliqué. Lecture seule[`IFillFormat`](../ifillformat) . |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Renvoie les propriétés LineFormat utilisées pour souligner la ligne de soulignement. Aucun héritage appliqué. Lecture seule[`ILineFormat`](../ilineformat) . |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage de la portion de texte définies pour la portion particulière. Cela signifie que aucun héritage n'est appliqué lors de l'obtention de valeurs, donc dans la majorité des cas, vous obtiendrez des valeurs signifiant "indéfini".

Afin d'obtenir les valeurs de paramètre de formatage efficaces, y compris héritées, vous devez utiliser[`GetEffective`](../iportionformat/geteffective) méthode qui renvoie un[`IPortionFormatEffectiveData`](../iportionformateffectivedata) exemple.

### Voir également

* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
