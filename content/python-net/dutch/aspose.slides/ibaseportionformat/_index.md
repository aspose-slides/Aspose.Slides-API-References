---
title: IBasePortionFormat class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat klasse

Deze klasse bevat de opmaak-eigenschappen van tekstgedeelten. In tegenstelling tot [`IPortionFormatEffectiveData`](/slides/python-net/nl/aspose.slides/iportionformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

Het type IBasePortionFormat exposeert de volgende leden:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/nl/aspose.slides/ibaseportionformat/line_format/) | Retourneert de LineFormat-eigenschappen voor tekstopmaak. Geen overerving toegepast.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/ibaseportionformat/fill_format/) | Retourneert de FillFormat-eigenschappen van de tekst. Geen overerving toegepast.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/ibaseportionformat/effect_format/) | Retourneert de EffectFormat-eigenschappen van de tekst. Geen overerving toegepast.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/nl/aspose.slides/ibaseportionformat/highlight_color/) | Retourneert de kleur die wordt gebruikt om tekst te markeren. Geen overerving toegepast.<br/>            Alleen-lezen [`IColorFormat`](/slides/python-net/nl/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/nl/aspose.slides/ibaseportionformat/underline_line_format/) | Retourneert de LineFormat-eigenschappen die worden gebruikt om de onderstrepingslijn te omlijnen. Geen overerving toegepast.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/nl/aspose.slides/ibaseportionformat/underline_fill_format/) | Retourneert de FillFormat-eigenschappen van de onderstrepingslijn. Geen overerving toegepast.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/nl/aspose.slides/ibaseportionformat/font_bold/) | Bepaalt of het lettertype vet is. Geen overerving toegepast.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/nl/aspose.slides/ibaseportionformat/font_italic/) | Bepaalt of het lettertype cursief is. Geen overerving toegepast.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/nl/aspose.slides/ibaseportionformat/kumimoji/) | Bepaalt of cijfers de oosterse taal-specifieke verticale tekstindeling moeten negeren. Geen overerving toegepast.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/nl/aspose.slides/ibaseportionformat/normalise_height/) | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/nl/aspose.slides/ibaseportionformat/proof_disabled/) | Bepaalt of de tekst niet gecontroleerd mag worden. Geen overerving toegepast.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/nl/aspose.slides/ibaseportionformat/font_underline/) | Retourneert of stelt het onderstreeptype van de tekst in. Geen overerving toegepast.<br/>            Lezen/schrijven [`TextUnderlineType`](/slides/python-net/nl/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/nl/aspose.slides/ibaseportionformat/text_cap_type/) | Retourneert of stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast.<br/>            Lezen/schrijven [`TextCapType`](/slides/python-net/nl/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/nl/aspose.slides/ibaseportionformat/strikethrough_type/) | Retourneert of stelt het doorhalingsstype van een tekst in. Geen overerving toegepast.<br/>            Lezen/schrijven [`TextStrikethroughType`](/slides/python-net/nl/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/nl/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Bepaalt of de onderstrepingsstijl eigen LineFormat-eigenschappen heeft of deze erft<br/>            van de LineFormat-eigenschappen van de tekst.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/nl/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Bepaalt of de onderstrepingsstijl eigen FillFormat-eigenschappen heeft of deze erft<br/>            van de FillFormat-eigenschappen van de tekst.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/nl/aspose.slides/ibaseportionformat/font_height/) | Retourneert of stelt de letterhoogte van een gedeelte in.<br/>            **float.NaN**  betekent dat de hoogte niet is gedefinieerd en moet worden geërfd van de Master.<br/>            Lezen/schrijven **float**. |
| [`latin_font`](/slides/python-net/nl/aspose.slides/ibaseportionformat/latin_font/) | Retourneert of stelt de Latijnse lettertype-info in.<br/>            Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master.<br/>            Lezen/schrijven [`IFontData`](/slides/python-net/nl/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/nl/aspose.slides/ibaseportionformat/east_asian_font/) | Retourneert of stelt de Oost-Aziatische lettertype-info in.<br/>            Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master.<br/>            Lezen/schrijven [`IFontData`](/slides/python-net/nl/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/nl/aspose.slides/ibaseportionformat/complex_script_font/) | Retourneert of stelt de complexe script-lettertype-info in.<br/>            Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master.<br/>            Lezen/schrijven [`IFontData`](/slides/python-net/nl/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/nl/aspose.slides/ibaseportionformat/symbol_font/) | Retourneert of stelt de symbolische lettertype-info in.<br/>            Null betekent dat het lettertype niet is gedefinieerd en moet worden geërfd van de Master.<br/>            Lezen/schrijven [`IFontData`](/slides/python-net/nl/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/nl/aspose.slides/ibaseportionformat/escapement/) | Retourneert of stelt de superscript- of subscript-tekst in.<br/>            Waarde van -100% (subscript) tot 100% (superscript).<br/>            **float.NaN**  betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master.<br/>            Lezen/schrijven **float**. |
| [`kerning_minimal_size`](/slides/python-net/nl/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Retourneert of stelt de minimale lettergrootte in, waarvoor kerning moet worden ingeschakeld.<br/>            **float.NaN**  betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master.<br/>            Lezen/schrijven **float**. |
| [`language_id`](/slides/python-net/nl/aspose.slides/ibaseportionformat/language_id/) | Retourneert of stelt de Id van een proeftaal in. Wordt gebruikt voor spelling- en grammaticacontrole.<br/>            Lezen/schrijven **str**. |
| [`alternative_language_id`](/slides/python-net/nl/aspose.slides/ibaseportionformat/alternative_language_id/) | Retourneert of stelt de Id van een alternatieve taal in.<br/>            Lezen/schrijven **str**. |
| [`spacing`](/slides/python-net/nl/aspose.slides/ibaseportionformat/spacing/) | Retourneert of stelt de interkarakter-spatiëringsstap in.<br/>            **float.NaN**  betekent dat de waarde niet is gedefinieerd en moet worden geërfd van de Master.<br/>            Lezen/schrijven **float**. |
| [`spell_check`](/slides/python-net/nl/aspose.slides/ibaseportionformat/spell_check/) | Retourneert of stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte.<br/>            Wanneer deze eigenschap op false staat, worden spellingcontroles voor textelementen onderdrukt.<br/>            Wanneer ingesteld op true, is spellingscontrole toegestaan.<br/>            Standaardwaarde is `false`. |

### Opmerkingen

Deze klasse wordt gebruikt om de opmaak-eigenschappen van een tekstgedeelte op te halen en te manipuleren die voor het specifieke gedeelte zijn gedefinieerd. Dit betekent dat
            er geen overerving wordt toegepast bij het ophalen van waarden, zodat je in de meeste gevallen waarden krijgt die "onbepaald" betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde, te verkrijgen, moet je de [`IPortionFormat.get_effective`](/slides/python-net/nl/aspose.slides/iportionformat/get_effective)-methode gebruiken
            die een [`IPortionFormatEffectiveData`](/slides/python-net/nl/aspose.slides/iportionformateffectivedata)-instantie retourneert.

### Zie ook
* klasse [`IPortionFormatEffectiveData`](/slides/python-net/nl/aspose.slides/iportionformateffectivedata)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)