---
title: BasePortionFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Algemene opmaak-eigenschappen voor tekstdelen.
type: docs
weight: 970
url: /nl/aspose.slides/baseportionformat/
---
## BasePortionFormat klasse

Algemene opmaak-eigenschappen voor tekstdelen.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Retourneert of stelt de Id in van een alternatieve taal. Lezen/schrijven String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Stelt de base IPresentationComponent-interface beschikbaar. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Retourneert of stelt de complexe script-lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Retourneert of stelt de Oost-Aziatische lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Retourneert de EffectFormat-eigenschappen van de tekst. Geen overerving toegepast. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Retourneert of stelt superscript- of subscript-tekst in. Waarde van -100% (subscript) tot 100% (superscript). **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Retourneert de FillFormat-eigenschappen van de tekst. Geen overerving toegepast. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bepaalt of het lettertype vet is. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Retourneert of stelt de letterhoogte van een deel in. **float.NaN** betekent dat de hoogte niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Retourneert of stelt het onderstreeptype van de tekst in. Geen overerving toegepast. Lezen/schrijven [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Retourneert de kleur die wordt gebruikt om een tekst te markeren. Geen overerving toegepast. Alleen-lezen [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bepaalt of de onderstreeptype eigen FillFormat-eigenschappen heeft of deze erft van de FillFormat-eigenschappen van de tekst. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bepaalt of de onderstreeptype eigen LineFormat-eigenschappen heeft of deze erft van de LineFormat-eigenschappen van de tekst. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Retourneert of stelt de minimale lettergrootte in, waarvoor kerning moet worden ingeschakeld. **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bepaalt of de getallen de oost-Aziatische specifieke verticale tekstlay-out van de tekst moeten negeren. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Retourneert of stelt de Id in van een proefleestaal. Wordt gebruikt voor spelling- en grammaticacontrole. Lezen/schrijven String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Retourneert of stelt de Latijnse lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Retourneert de LineFormat-eigenschappen voor het omranden van tekst. Geen overerving toegepast. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bepaalt of de tekst niet gecontroleerd mag worden. Geen overerving toegepast. Lezen/schrijven [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Retourneert of stelt de interkarakter-spatiëringsincrement in. **float.NaN** betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Haalt of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstdeling. Wanneer deze eigenschap op false is gezet, worden spellingcontroles voor tekstelementen onderdrukt. Wanneer op true gezet, is spellingscontrole toegestaan. Standaardwaarde is `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Retourneert of stelt het doorstreeptype van een tekst in. Geen overerving toegepast. Lezen/schrijven [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Retourneert of stelt de symbolische lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master. Lezen/schrijven [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Retourneert of stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast. Lezen/schrijven [`TextCapType`](../textcaptype). |
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
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->