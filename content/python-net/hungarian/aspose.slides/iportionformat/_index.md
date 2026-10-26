---
title: IPortionFormat class
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozásán keresztül
description: 
type: docs
url: /hu/aspose.slides/iportionformat/
---
## IPortionFormat osztály

Ez az osztály a szövegrész formázási tulajdonságait tartalmazza. A [`IPortionFormatEffectiveData`](/slides/python-net/hu/aspose.slides/iportionformateffectivedata)-tól eltérően az osztály összes tulajdonsága írható.

Az IPortionFormat típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`bookmark_id`](/slides/python-net/hu/aspose.slides/iportionformat/bookmark_id/) | Visszaadja vagy beállítja a könyvjelző azonosítóját.<br/>            Olvasás/írás **str**. |
| [`smart_tag_clean`](/slides/python-net/hu/aspose.slides/iportionformat/smart_tag_clean/) | Meghatározza, hogy a okos címkét tisztítani kell-e. Nincs öröklődés alkalmazva.<br/>            Olvasás/írás **bool**. |
| [`line_format`](/slides/python-net/hu/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/hu/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/hu/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/hu/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/hu/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/hu/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/hu/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/hu/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/hu/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/hu/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/hu/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/hu/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/hu/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/hu/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/hu/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/hu/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/hu/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/hu/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/hu/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/hu/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/hu/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/hu/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/hu/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/hu/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/hu/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/hu/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/hu/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/iportionformat/hyperlink_manager/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/hu/aspose.slides/iportionformat/get_effective/#) | Megkapja a hatékony szövegrész formázási adatokat az öröklődés alkalmazásával. |


### Megjegyzés

Ez az osztály a konkrét szakaszra definiált szövegrész formázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy
            az értékek lekérésekor nincs öröklődés alkalmazva, így a legtöbb esetben olyan értékeket kapsz, amelyek „nem definiált” jelentésűek.

Az örökölt értékeket is tartalmazó hatékony formázási paraméterértékek lekéréséhez használni kell a [`IPortionFormat.get_effective`](/slides/python-net/hu/aspose.slides/iportionformat/get_effective) metódust 
            amely egy [`IPortionFormatEffectiveData`](/slides/python-net/hu/aspose.slides/iportionformateffectivedata) példányt ad vissza.

### Lásd még
* osztály [`IPortionFormatEffectiveData`](/slides/python-net/hu/aspose.slides/iportionformateffectivedata)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)