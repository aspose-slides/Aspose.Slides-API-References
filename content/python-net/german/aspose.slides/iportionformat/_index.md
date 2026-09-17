---
title: IPortionFormat class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iportionformat/
---
## IPortionFormat Klasse

Diese Klasse enthält die Textabschnitt-Formatierungseigenschaften. Im Gegensatz zu [`IPortionFormatEffectiveData`](/slides/python-net/de/aspose.slides/iportionformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

Der Typ IPortionFormat stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`bookmark_id`](/slides/python-net/de/aspose.slides/iportionformat/bookmark_id/) | Liefert oder setzt die Lesezeichen-ID.<br/>            Lesen/Schreiben **str**. |
| [`smart_tag_clean`](/slides/python-net/de/aspose.slides/iportionformat/smart_tag_clean/) | Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet.<br/>            Lesen/Schreiben **bool**. |
| [`line_format`](/slides/python-net/de/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/de/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/de/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/de/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/de/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/de/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/de/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/de/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/de/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/de/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/de/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/de/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/de/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/de/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/de/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/de/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/de/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/de/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/de/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/de/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/de/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/de/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/de/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/de/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/de/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/de/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/de/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/iportionformat/hyperlink_manager/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/de/aspose.slides/iportionformat/get_effective/#) | Liefert die effektiven Formatierungsdaten des Abschnitts mit angewandter Vererbung. |

### Bemerkungen

Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Textabschnitt-Formatierungseigenschaften zurückzugeben und zu bearbeiten. Das bedeutet, dass
            keine Vererbung angewendet wird, wenn Werte abgerufen werden, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die [`IPortionFormat.get_effective`](/slides/python-net/de/aspose.slides/iportionformat/get_effective) Methode verwenden,
            die eine [`IPortionFormatEffectiveData`](/slides/python-net/de/aspose.slides/iportionformateffectivedata) Instanz zurückgibt.

### Siehe auch
* Klasse [`IPortionFormatEffectiveData`](/slides/python-net/de/aspose.slides/iportionformateffectivedata)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)