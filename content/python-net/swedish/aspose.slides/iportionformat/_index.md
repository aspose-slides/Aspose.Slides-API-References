---
title: IPortionFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iportionformat/
---
## IPortionFormat klass

Denna klass innehåller textdelens formateringsegenskaper. Till skillnad från [`IPortionFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

IPortionFormat-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`bookmark_id`](/slides/python-net/sv/aspose.slides/iportionformat/bookmark_id/) | Returnerar eller anger bokmärkesidentifierare.<br/>            Läs/skriv **str**. |
| [`smart_tag_clean`](/slides/python-net/sv/aspose.slides/iportionformat/smart_tag_clean/) | Bestämmer om smarttaggen ska rensas. Ingen arv tillämpas.<br/>            Läs/skriv **bool**. |
| [`line_format`](/slides/python-net/sv/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/sv/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/sv/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/sv/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/sv/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/sv/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/sv/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/sv/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/sv/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/sv/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/sv/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/sv/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/sv/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/sv/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/sv/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/sv/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/sv/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/sv/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/sv/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/sv/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/sv/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/sv/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/sv/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/sv/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/sv/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/sv/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/sv/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/iportionformat/hyperlink_manager/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/sv/aspose.slides/iportionformat/get_effective/#) | Hämtar effektiv formateringsdata för portionen med ärvd tillämpning. |

### Anmärkningar

Denna klass används för att returnera och manipulera formateringsegenskaper för textdelen som definierats för den specifika delen. Detta innebär att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierad".

För att få de effektiva formatparametrarna inklusive ärvda måste du använda [`IPortionFormat.get_effective`](/slides/python-net/sv/aspose.slides/iportionformat/get_effective)-metoden som returnerar en [`IPortionFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iportionformateffectivedata)-instans.

### Se även
* klass [`IPortionFormatEffectiveData`](/slides/python-net/sv/aspose.slides/iportionformateffectivedata)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)