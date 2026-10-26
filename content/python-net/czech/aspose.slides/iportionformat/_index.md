---
title: IPortionFormat class
second_title: Aspose.Slides pro Python prostřednictvím .NET API
description: 
type: docs
url: /cs/aspose.slides/iportionformat/
---
## IPortionFormat třída

Tato třída obsahuje vlastnosti formátování textových úseků. Na rozdíl od [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

Typ IPortionFormat zveřejňuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`bookmark_id`](/slides/python-net/cs/aspose.slides/iportionformat/bookmark_id/) | Returns or sets bookmark identifier.<br/>            Čtení/zápis **str**. |
| [`smart_tag_clean`](/slides/python-net/cs/aspose.slides/iportionformat/smart_tag_clean/) | Determines whether the smart tag should be cleaned. No inheritance applied.<br/>            Čtení/zápis **bool**. |
| [`line_format`](/slides/python-net/cs/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/cs/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/cs/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/cs/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/cs/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/cs/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/cs/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/cs/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/cs/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/cs/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/cs/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/cs/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/cs/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/cs/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/cs/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/cs/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/cs/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/cs/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/cs/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/cs/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/cs/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/cs/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/cs/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/cs/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/cs/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/cs/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/cs/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/iportionformat/hyperlink_manager/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/cs/aspose.slides/iportionformat/get_effective/#) | Získá efektivní data formátování úseku s použitím dědičnosti. |


### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování textových úseků definovanými pro konkrétní úsek. To znamená, že při získávání hodnot se nepoužije dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Aby bylo možné získat efektivní hodnoty parametrů formátování včetně zděděných, je nutné použít metodu [`IPortionFormat.get_effective`](/slides/python-net/cs/aspose.slides/iportionformat/get_effective), která vrací instanci [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata).


### Viz také
* třída [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)