---
title: IPortionFormat class
second_title: Aspose.Slides dla Pythona przez .NET referencja API
description: 
type: docs
url: /pl/aspose.slides/iportionformat/
---
## IPortionFormat klasa

Ta klasa zawiera właściwości formatowania fragmentu tekstu. W przeciwieństwie do [`IPortionFormatEffectiveData`](/slides/python-net/pl/aspose.slides/iportionformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

Typ IPortionFormat udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`bookmark_id`](/slides/python-net/pl/aspose.slides/iportionformat/bookmark_id/) | Zwraca lub ustawia identyfikator zakładki.<br/>            Odczyt/zapis **str**. |
| [`smart_tag_clean`](/slides/python-net/pl/aspose.slides/iportionformat/smart_tag_clean/) | Określa, czy inteligentny znacznik powinien zostać wyczyszczony. Nie zastosowano dziedziczenia.<br/>            Odczyt/zapis **bool**. |
| [`line_format`](/slides/python-net/pl/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/pl/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/pl/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/pl/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/pl/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/pl/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/pl/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/pl/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/pl/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/pl/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/pl/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/pl/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/pl/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/pl/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/pl/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/pl/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/pl/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/pl/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/pl/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/pl/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/pl/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/pl/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/pl/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/pl/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/pl/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/pl/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/pl/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/iportionformat/hyperlink_manager/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/pl/aspose.slides/iportionformat/get_effective/#) | Pobiera skuteczne dane formatowania fragmentu z zastosowanym dziedziczeniem. |

### Uwagi

Ta klasa jest używana do zwracania i manipulacji właściwościami formatowania fragmentu tekstu zdefiniowanymi dla konkretnego fragmentu. Oznacza to, że
            nie jest stosowane dziedziczenie przy pobieraniu wartości, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać skuteczne wartości parametrów formatowania, w tym dziedziczone, należy użyć metody [`IPortionFormat.get_effective`](/slides/python-net/pl/aspose.slides/iportionformat/get_effective) 
            która zwraca instancję [`IPortionFormatEffectiveData`](/slides/python-net/pl/aspose.slides/iportionformateffectivedata).

### Zobacz także
* klasa [`IPortionFormatEffectiveData`](/slides/python-net/pl/aspose.slides/iportionformateffectivedata)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)