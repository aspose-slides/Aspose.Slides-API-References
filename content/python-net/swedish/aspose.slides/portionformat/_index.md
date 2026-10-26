---
title: PortionFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/portionformat/
---
## PortionFormat klass

Denna klass innehåller formateringsegenskaperna för textdelar. Till skillnad från [`IPortionFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

**Arv:**[`PortionFormat`](/slides/python-net/sv/aspose.slides/portionformat) → [`BasePortionFormat`](/slides/python-net/sv/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)

PortionFormat-typen exponerar följande medlemmar:

## Constructors

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides/portionformat/__init__/#) | Initialiserar en ny instans av [`PortionFormat`](/slides/python-net/sv/aspose.slides/portionformat) klass. |

## Properties

| Egenskap | Beskrivning |
| :- | :- |
| [`line_format`](/slides/python-net/sv/aspose.slides/portionformat/line_format/) | Returnerar LineFormat-egenskaperna för textkontur. Ingen arv tillämpas.<br/>            Endast läsning [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/portionformat/fill_format/) | Returnerar textens FillFormat-egenskaper. Ingen arv tillämpas.<br/>            Endast läsning [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/portionformat/effect_format/) | Returnerar textens EffectFormat-egenskaper. Ingen arv tillämpas.<br/>            Endast läsning [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/sv/aspose.slides/portionformat/highlight_color/) | Returnerar färgen som används för att markera en text. Ingen arv tillämpas.<br/>            Endast läsning [`IColorFormat`](/slides/python-net/sv/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/sv/aspose.slides/portionformat/underline_line_format/) | Returnerar LineFormat-egenskaperna som används för att konturera understrykning. Ingen arv tillämpas.<br/>            Endast läsning [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/sv/aspose.slides/portionformat/underline_fill_format/) | Returnerar understrykningens FillFormat-egenskaper. Ingen arv tillämpas.<br/>            Endast läsning [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/sv/aspose.slides/portionformat/font_bold/) | Avgör om teckensnittet är fetstil. Ingen arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/sv/aspose.slides/portionformat/font_italic/) | Avgör om teckensnittet är kursivt. Ingen arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/sv/aspose.slides/portionformat/kumimoji/) | Avgör om siffrorna ska ignorera den östasiatiska språk-specifika vertikala textlayouten. Ingen arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/sv/aspose.slides/portionformat/normalise_height/) | Avgör om höjden på en text ska normaliseras. Ingen arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/sv/aspose.slides/portionformat/proof_disabled/) | Avgör om texten inte ska korrekturläsas. Ingen arv tillämpas.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/sv/aspose.slides/portionformat/font_underline/) | Returnerar eller anger typen av textunderlinje. Ingen arv tillämpas.<br/>            Läs/skriv [`TextUnderlineType`](/slides/python-net/sv/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/sv/aspose.slides/portionformat/text_cap_type/) | Returnerar eller anger typen av textkapitalisering. Ingen arv tillämpas.<br/>            Läs/skriv [`TextCapType`](/slides/python-net/sv/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/sv/aspose.slides/portionformat/strikethrough_type/) | Returnerar eller anger genomstrykningstypen för en text. Ingen arv tillämpas.<br/>            Läs/skriv [`TextStrikethroughType`](/slides/python-net/sv/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/sv/aspose.slides/portionformat/is_hard_underline_line/) | Avgör om understrykningens stil har egna LineFormat-egenskaper eller ärver dem<br/>            från textens LineFormat-egenskaper.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/sv/aspose.slides/portionformat/is_hard_underline_fill/) | Avgör om understrykningens stil har egna FillFormat-egenskaper eller ärver dem<br/>            från textens FillFormat-egenskaper.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/sv/aspose.slides/portionformat/font_height/) | Returnerar eller anger teckenhöjden för en del.<br/>            **float.NaN** betyder att höjden är odefinierad och ska ärvas från Master.<br/>            Läs/skriv **float**. |
| [`latin_font`](/slides/python-net/sv/aspose.slides/portionformat/latin_font/) | Returnerar eller anger information om latinskt teckensnitt.<br/>            Null betyder att teckensnittet är odefinierat och ska ärvas från Master.<br/>            Läs/skriv [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/sv/aspose.slides/portionformat/east_asian_font/) | Returnerar eller anger information om östasiatiskt teckensnitt.<br/>            Null betyder att teckensnittet är odefinierat och ska ärvas från Master.<br/>            Läs/skriv [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/sv/aspose.slides/portionformat/complex_script_font/) | Returnerar eller anger information om komplext skriptteckensnitt.<br/>            Null betyder att teckensnittet är odefinierat och ska ärvas från Master.<br/>            Läs/skriv [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/sv/aspose.slides/portionformat/symbol_font/) | Returnerar eller anger information om symboliskt teckensnitt.<br/>            Null betyder att teckensnittet är odefinierat och ska ärvas från Master.<br/>            Läs/skriv [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/sv/aspose.slides/portionformat/escapement/) | Returnerar eller anger upphöjd eller nedsänkt text.<br/>            Värde från -100% (nedsänkt) till 100% (upphöjd).<br/>            **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master.<br/>            Läs/skriv **float**. |
| [`kerning_minimal_size`](/slides/python-net/sv/aspose.slides/portionformat/kerning_minimal_size/) | Returnerar eller anger den minsta teckenstorleken för vilken kerning ska aktiveras.<br/>            **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master.<br/>            Läs/skriv **float**. |
| [`language_id`](/slides/python-net/sv/aspose.slides/portionformat/language_id/) | Returnerar eller anger Id för ett korrekturspråk. Används för stavnings- och grammatikkontroll.<br/>            Läs/skriv **str**. |
| [`alternative_language_id`](/slides/python-net/sv/aspose.slides/portionformat/alternative_language_id/) | Returnerar eller anger Id för ett alternativt språk.<br/>            Läs/skriv **str**. |
| [`spacing`](/slides/python-net/sv/aspose.slides/portionformat/spacing/) | Returnerar eller anger interteckenavståndsincrementet.<br/>            **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master.<br/>            Läs/skriv **float**. |
| [`spell_check`](/slides/python-net/sv/aspose.slides/portionformat/spell_check/) | Hämtar eller anger ett värde som indikerar om stavningskontroll är aktiverad för textdelen.<br/>            När denna egenskap är inställd på false undertrycks stavningskontroller för textelement.<br/>            När den är inställd på true tillåts stavningskontroll.<br/>            Standardvärdet är `false`. |
| [`bookmark_id`](/slides/python-net/sv/aspose.slides/portionformat/bookmark_id/) | Returnerar eller anger bokmärkets identifierare.<br/>            Läs/skriv **str**. |
| [`smart_tag_clean`](/slides/python-net/sv/aspose.slides/portionformat/smart_tag_clean/) | Avgör om smart-taggen ska rensas. Ingen arv tillämpas.<br/>            Läs/skriv **bool**. |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/portionformat/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/portionformat/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för musöver.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/portionformat/hyperlink_manager/) | Hyperlänks hanterare.<br/>            Endast läsning [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`slide`](/slides/python-net/sv/aspose.slides/portionformat/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/portionformat/presentation/) |  |

## Methods

| Metod | Beskrivning |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/sv/aspose.slides/portionformat/get_effective/#) | Hämtar effektiv formatteringsdata för delen med arv tillämpat. |

### Anmärkningar

Denna klass används för att returnera och manipulera formateringsegenskaper för en specifik textdel. Detta innebär att
            ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparameter-värdena inklusive ärvda måste du använda metoden [`PortionFormat.get_effective`](/slides/python-net/sv/aspose.slides/portionformat/get_effective) 
            som returnerar en [`IPortionFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iportionformateffectivedata)-instans.

### Se också
* klass [`BasePortionFormat`](/slides/python-net/sv/aspose.slides/baseportionformat)
* klass [`IPortionFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iportionformateffectivedata)
* klass [`PortionFormat`](/slides/python-net/sv/aspose.slides/portionformat)
* klass [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)