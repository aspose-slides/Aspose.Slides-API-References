---
title: BasePortionFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Algemene opmaak-eigenschappen voor tekstdelen.
type: docs
weight: 970
url: /nl/aspose.slides/baseportionformat/
---
## BasePortionFormat klasse

Gemeenschappelijke tekstgedeeltelijke opmaak eigenschappen.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retourneert of stelt de Id van een alternatieve taal in. Lezen/Schrijven String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Maakt het mogelijk om de basis-IPresentationComponent-interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retourneert of stelt de complexe script-lettertype-info in. Null betekent dat lettertype niet is gedefinieerd en van de Master moet worden geërfd. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retourneert of stelt de Oost-Aziatische lettertype-info in. Null betekent dat lettertype niet is gedefinieerd en van de Master moet worden geërfd. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retourneert de EffectFormat-eigenschappen van de tekst. Geen overerving toegepast. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retourneert of stelt de superscript- of subscript-tekst in. Waarde van -100 % (subscript) tot 100 % (superscript). **float.NaN** betekent dat de waarde niet is gedefinieerd en van de Master moet worden geërfd. Lezen/Schrijven Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retourneert de FillFormat-eigenschappen van de tekst. Geen overerving toegepast. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bepaalt of het lettertype vet is. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retourneert of stelt de letterhoogte van een gedeelte in. **float.NaN** betekent dat de hoogte niet is gedefinieerd en van de Master moet worden geërfd. Lezen/Schrijven Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retourneert of stelt het onderstreeptype van de tekst in. Geen overerving toegepast. Lezen/Schrijven [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retourneert de kleur die wordt gebruikt om tekst te markeren. Geen overerving toegepast. Alleen-lezen [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bepaalt of de onderstreeleigenschappen een eigen FillFormat hebben of die van de tekst overnemen. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bepaalt of de onderstreeleigenschappen een eigen LineFormat hebben of die van de tekst overnemen. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retourneert of stelt de minimale lettergrootte in waarvoor kerning moet worden ingeschakeld. **float.NaN** betekent dat de waarde niet is gedefinieerd en van de Master moet worden geërfd. Lezen/Schrijven Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bepaalt of getallen de oost-Aziatische taal-specifieke verticale tekstlay-out moeten negeren. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retourneert of stelt de Id van een controle-taal in. Wordt gebruikt voor spelling- en grammaticacontrole. Lezen/Schrijven String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retourneert of stelt de Latijnse lettertype-info in. Null betekent dat lettertype niet is gedefinieerd en van de Master moet worden geërfd. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retourneert de LineFormat-eigenschappen voor tekstomlijning. Geen overerving toegepast. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bepaalt of de tekst niet moet worden gecontroleerd. Geen overerving toegepast. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retourneert of stelt de inter-karakter-spatiërings-increment in. **float.NaN** betekent dat de waarde niet is gedefinieerd en van de Master moet worden geërfd. Lezen/Schrijven Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Haalt of stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Als deze eigenschap op false staat, worden spellingcontroles voor textelementen onderdrukt. Als hij op true staat, is spellingcontrole toegestaan. Standaardwaarde is `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retourneert of stelt het doorhalings-type van een tekst in. Geen overerving toegepast. Lezen/Schrijven [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retourneert of stelt de symbolische lettertype-info in. Null betekent dat lettertype niet is gedefinieerd en van de Master moet worden geërfd. Lezen/Schrijven [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retourneert of stelt het type hoofdlettergebruik in. Geen overerving toegepast. Lezen/Schrijven [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Retourneert de FillFormat-eigenschappen van de onderstreeplijn. Geen overerving toegepast. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstreeplijn te omlijnen. Geen overerving toegepast. Alleen-lezen [`ILineFormat`](../ilineformat). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met het opgegeven object. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourneert hashcode. |

### Zie ook

* klasse [PVIObject](../pviobject)
* interface [IBasePortionFormat](../ibaseportionformat)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->