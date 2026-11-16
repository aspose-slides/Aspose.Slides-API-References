---
title: PortionFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Deze klasse bevat de tekstgedeelte-opmaak-eigenschappen. In tegenstelling tot IPortionFormatEffectiveData./iportionformateffectivedata zijn alle eigenschapen van deze klasse schrijfbaar.
type: docs
weight: 9510
url: /nl/aspose.slides/portionformat/
---
## PortionFormat klasse

Deze klasse bevat de tekstgedeelte-opmaak-eigenschappen. In tegenstelling tot [`IPortionFormatEffectiveData`](../iportionformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [PortionFormat](portionformat)() | Initialiseert een nieuwe instantie van de [`PortionFormat`](../portionformat) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retourneert of stelt de Id van een alternatieve taal in. Lezen/Schrijven String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Stelt toe om de basis IPresentationComponent interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Retourneert of stelt de bladwijzer-identifier in. Lezen/Schrijven String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retourneert of stelt de complexe script-lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en overgeërfd moet worden van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retourneert of stelt de Oost-Aziatische lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en overgeërfd moet worden van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retourneert de tekst EffectFormat-eigenschappen. Geen overerving toegepast. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retourneert of stelt de superscript- of subscript-tekst in. Waarde van -100% (subscript) tot 100% (superscript). **float.NaN** betekent dat de waarde ongedefinieerd is en overgeërfd moet worden van de Master. Lezen/Schrijven Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retourneert de tekst FillFormat-eigenschappen. Geen overerving toegepast. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bepaalt of het lettertype vet is. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retourneert of stelt de lettertype-hoogte van een gedeelte in. **float.NaN** betekent dat de hoogte ongedefinieerd is en overgeërfd moet worden van de Master. Lezen/Schrijven Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retourneert of stelt het onderstreeptype van de tekst in. Geen overerving toegepast. Lezen/Schrijven [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retourneert de kleur die wordt gebruikt om tekst te markeren. Geen overerving toegepast. Alleen-lezen [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hyperlinks manager. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bepaalt of de onderstreeleigenschap eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bepaalt of de onderstreeleigenschap eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retourneert of stelt de minimale lettertypegrootte in waarvoor kerning moet worden ingeschakeld. **float.NaN** betekent dat de waarde ongedefinieerd is en overgeërfd moet worden van de Master. Lezen/Schrijven Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bepaalt of de cijfers de oost-taal-specifieke verticale tekstopmaak moeten negeren. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retourneert of stelt de Id van een proefleestaal in. Wordt gebruikt voor spelling- en grammaticacontrole. Lezen/Schrijven String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retourneert of stelt de Latijnse lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en overgeërfd moet worden van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retourneert de LineFormat-eigenschappen voor tekstopvolging. Geen overerving toegepast. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bepaalt of de tekst niet proefgelezen moet worden. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Bepaalt of de smart-tag moet worden opgeschoond. Geen overerving toegepast. Lezen/Schrijven Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retourneert of stelt de interkarakter-spatiërings-increment in. **float.NaN** betekent dat de waarde ongedefinieerd is en overgeërfd moet worden van de Master. Lezen/Schrijven Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Haalt een waarde op of stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap `false` is, worden spellingcontroles voor tekstelementen onderdrukt. Wanneer `true`, is spellingcontrole toegestaan. Standaardwaarde is `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retourneert of stelt het doorhalings-type van een tekst in. Geen overerving toegepast. Lezen/Schrijven [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retourneert of stelt de symbolische lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en overgeërfd moet worden van de Master. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retourneert of stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast. Lezen/Schrijven [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retourneert de onderstrepingslijn FillFormat-eigenschappen. Geen overerving toegepast. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstrepingslijn te omlijnen. Geen overerving toegepast. Alleen-lezen [`ILineFormat`](../ilineformat). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met het opgegeven object. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Haalt effectieve gedeelte-opmaakgegevens op met de toegepaste overerving. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourneert hash-code. |

### Opmerkingen

Deze klasse wordt gebruikt om de tekstgedeelte-opmaak-eigenschappen die voor een specifiek gedeelte zijn gedefinieerd, op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat in de meeste gevallen waarden returned worden die betekenen “ongedefinieerd”.

Om de effectieve opmaak-parameterwaarden inclusief geërfde waarden te verkrijgen, moet u de [`GetEffective`](./geteffective)-methode gebruiken die een [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-instantie retourneert.

### Voorbeelden

De volgende voorbeelden tonen hoe u het Latijnse lettertype toewijst aan een gedeelte van een Paragraph in een PowerPoint-presentatie.

```csharp
[C#]
//Maak een presentatie-object dat een presentatie-bestand voorstelt
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides gebruikt deze speciale identifiers (vergelijkbaar met die in PowerPoint):
// +mn-lt - Body-lettertype Latin (Minor Latin Font)
// +mj-lt -Heading-lettertype Latin (Major Latin Font)
// +mn-ea - Body-lettertype East Asian (Minor East Asian Font)
// +mj-ea - Body-lettertype East Asian (Minor East Asian Font)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Zie ook

* klasse [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->