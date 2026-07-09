---
title: PortionFormat
second_title: Aspose.Slides voor .NET API-referentie
description: Deze klasse bevat de opmaak-eigenschappen voor tekstporties. In tegenstelling tot IPortionFormatEffectiveData./iportionformateffectivedata zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 9490
url: /nl/aspose.slides/portionformat/
---
## PortionFormat klasse

Deze klasse bevat de opmaak-eigenschappen voor tekstporties. In tegenstelling tot [`IPortionFormatEffectiveData`](../iportionformateffectivedata), zijn alle eigenschappen van deze klasse schrijfbaar.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Constructors

| Naam | Omschrijving |
| --- | --- |
| [PortionFormat](portionformat)() | Initialiseert een nieuw exemplaar van [`PortionFormat`](../portionformat) klasse. |

## Eigenschappen

| Naam | Omschrijving |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retourneert of stelt de Id van een alternatieve taal in. Lezen/schrijven String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Maakt het mogelijk om de basis-IPresentationComponent-interface te verkrijgen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Retourneert of stelt de bladwijzer-identificatie in. Lezen/schrijven String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retourneert of stelt de complexe script-lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retourneert of stelt de Oost-Azia-lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retourneert de tekst-EffectFormat-eigenschappen. Geen overerving toegepast. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retourneert of stelt de superscript- of subscript-tekst in. Waarde van -100 % (subscript) tot 100 % (superscript). **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retourneert de tekst-FillFormat-eigenschappen. Geen overerving toegepast. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bepaalt of het lettertype vetgedrukt is. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retourneert of stelt de letterhoogte van een portie in. **float.NaN** betekent dat de hoogte niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retourneert of stelt het onderstrepingstype van de tekst in. Geen overerving toegepast. Lezen/schrijven [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retourneert de kleur die wordt gebruikt om tekst te markeren. Geen overerving toegepast. Alleen-lezen [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hyperlinks-beheerder. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bepaalt of de onderstrepingsstijl eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bepaalt of de onderstrepingsstijl eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retourneert of stelt de minimale lettergrootte in waarvoor kerning moet worden ingeschakeld. **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bepaalt of de getallen de oost-Azia-specifieke verticale lay-out van de tekst moeten negeren. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retourneert of stelt de Id van een proefleestaal in. Wordt gebruikt voor spelling- en grammaticacontrole. Lezen/schrijven String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retourneert of stelt de Latijnse lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retourneert de LineFormat-eigenschappen voor tekstomlijning. Geen overerving toegepast. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bepaalt of de hoogte van een tekst moet worden genormaliseerd. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bepaalt of de tekst niet moet worden gecontroleerd. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Bepaalt of de smart-tag moet worden opgeschoond. Geen overerving toegepast. Lezen/schrijven Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retourneert of stelt de increment voor interkarakter-afstand in. **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Krijgt of stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor de tekstportie. Wanneer deze eigenschap op false staat, wordt spellingcontrole voor textelementen onderdrukt. Wanneer ingesteld op true, is spellingcontrole toegestaan. Standaardwaarde is `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retourneert of stelt het doorstrepings-type van een tekst in. Geen overerving toegepast. Lezen/schrijven [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retourneert of stelt de symbolische lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retourneert of stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast. Lezen/schrijven [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retourneert de FillFormat-eigenschappen van de onderstrepingslijn. Geen overerving toegepast. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstrepingslijn te omlijnen. Geen overerving toegepast. Alleen-lezen [`ILineFormat`](../ilineformat). |

## Methodes

| Naam | Omschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met het opgegeven object. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Haalt de effectieve portie-opmaakgegevens op met de toegepaste overerving. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourneert de hashcode. |

### Opmerkingen

Deze klasse wordt gebruikt om de tekstportie-opmaak-eigenschappen die voor de specifieke portie zijn gedefinieerd, op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, waardoor in de meeste gevallen waarden worden geretourneerd die “ongedefinieerd” betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde, te verkrijgen, moet u de [`GetEffective`](./geteffective)-methode gebruiken, die een [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-instantie retourneert.

### Voorbeelden

Het volgende voorbeeld toont hoe u het Latijnse lettertype kunt toewijzen aan een Paragraph-portie van een PowerPoint-presentatie.

```csharp
[C#]
//Instancieer een presentatie-object dat een presentatie-bestand vertegenwoordigt
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides gebruikt deze speciale identifiers (vergelijkbaar met die in PowerPoint):
// +mn-lt - Body-lettertype Latin (Minor Latin Font)
// +mj-lt - Heading-lettertype Latin (Major Latin Font)
// +mn-ea - Body-lettertype East Asian (Minor East Asian Font)
// +mj-ea - Body-lettertype East Asian (Minor East Asian Font)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Zie ook

* klasse [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->