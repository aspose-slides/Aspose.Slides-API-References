---
title: IBasePortionFormat
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Cette classe contient les propriétés de mise en forme des portions de texte. Contrairement à IPortionFormatEffectiveData./iportionformateffectivedata toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 5310
url: /fr/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interface

Cette classe contient les propriétés de mise en forme des portions de texte. Contrairement à [`IPortionFormatEffectiveData`](../iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

```csharp
public interface IBasePortionFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Renvoie ou définit l’Id d’une langue alternative. Lecture/écriture String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Renvoie ou définit les informations de police pour les scripts complexes. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Renvoie ou définit les informations de police Asie de l’Est. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Renvoie les propriétés EffectFormat du texte. Aucun héritage appliqué. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Renvoie ou définit le texte en exposant ou indice. Valeur de -100 % (indice) à 100 % (exposant). **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Renvoie les propriétés FillFormat du texte. Aucun héritage appliqué. Lecture seule [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Détermine si la police est en gras. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Renvoie ou définit la hauteur de police d’une portion. **float.NaN** signifie que la hauteur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Détermine si la police est italique. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué. Lecture/écriture [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Renvoie la couleur utilisée pour mettre en surbrillance du texte. Aucun héritage appliqué. Lecture seule [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lecture/écriture [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lecture/écriture [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Renvoie ou définit la taille minimale de police pour laquelle le crénage doit être activé. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Détermine si les chiffres doivent ignorer la disposition verticale du texte spécifique aux langues orientales. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Renvoie ou définit l'Id d'une langue de révision. Utilisée pour la vérification de l'orthographe et de la grammaire. Lecture/écriture String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Renvoie ou définit les informations de police latine. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Renvoie les propriétés LineFormat pour le contour du texte. Aucun héritage appliqué. Lecture seule [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Détermine si la hauteur du texte doit être normalisée. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Détermine si le texte ne doit pas être révisé. Aucun héritage appliqué. Lecture/écriture [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Renvoie ou définit l'incrément d'espacement inter-caractères. **float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Obtient ou définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Renvoie ou définit le type de barré du texte. Aucun héritage appliqué. Lecture/écriture [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Renvoie ou définit les informations de police symbolique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué. Lecture/écriture [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Renvoie les propriétés FillFormat de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Renvoie les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [`ILineFormat`](../ilineformat). |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de mise en forme des portions de texte définies pour la portion spécifique. Cela signifie qu'aucun héritage n'est appliqué lors de l'obtention des valeurs, de sorte que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de mise en forme, y compris celles héritées, vous devez utiliser la méthode [`GetEffective`](../iportionformat/geteffective) qui renvoie une instance [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Voir aussi

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->