---
title: BasePortionFormat class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/baseportionformat/
---
## BasePortionFormat Klasse

Gemeinsame Formatierungseigenschaften für Textabschnitte.

**Vererbung:**[`BasePortionFormat`](/slides/python-net/de/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/de/aspose.slides/pviobject)

Der BasePortionFormat-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/de/aspose.slides/baseportionformat/line_format/) | Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/baseportionformat/fill_format/) | Gibt die FillFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/baseportionformat/effect_format/) | Gibt die EffectFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/de/aspose.slides/baseportionformat/highlight_color/) | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet.<br/>            Nur lesbar [`IColorFormat`](/slides/python-net/de/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/de/aspose.slides/baseportionformat/underline_line_format/) | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/de/aspose.slides/baseportionformat/underline_fill_format/) | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/de/aspose.slides/baseportionformat/font_bold/) | Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/de/aspose.slides/baseportionformat/font_italic/) | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/de/aspose.slides/baseportionformat/kumimoji/) | Bestimmt, ob die Zahlen das textabhängige, ostasiatisch-spezifische vertikale Textlayout ignorieren sollen. Keine Vererbung angewendet.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/de/aspose.slides/baseportionformat/normalise_height/) | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/de/aspose.slides/baseportionformat/proof_disabled/) | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/de/aspose.slides/baseportionformat/font_underline/) | Gibt den Unterstreichungstyp des Textes zurück oder legt ihn fest. Keine Vererbung angewendet.<br/>            Lese/Schreib [`TextUnderlineType`](/slides/python-net/de/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/de/aspose.slides/baseportionformat/text_cap_type/) | Gibt die Art der Groß-/Kleinschreibung des Textes zurück oder legt sie fest. Keine Vererbung angewendet.<br/>            Lese/Schreib [`TextCapType`](/slides/python-net/de/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/de/aspose.slides/baseportionformat/strikethrough_type/) | Gibt den Durchstreichtyp eines Textes zurück oder legt ihn fest. Keine Vererbung angewendet.<br/>            Lese/Schreib [`TextStrikethroughType`](/slides/python-net/de/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/de/aspose.slides/baseportionformat/is_hard_underline_line/) | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie erbt<br/>            von den LineFormat-Eigenschaften des Textes.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/de/aspose.slides/baseportionformat/is_hard_underline_fill/) | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie erbt<br/>            von den FillFormat-Eigenschaften des Textes.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/de/aspose.slides/baseportionformat/font_height/) | Gibt die Schriftgröße eines Abschnitts zurück oder legt sie fest.<br/>            **float.NaN** bedeutet, dass die Höhe nicht definiert ist und vom Master geerbt werden sollte.<br/>            Lese/Schreib **float**. |
| [`latin_font`](/slides/python-net/de/aspose.slides/baseportionformat/latin_font/) | Gibt die Informationen zur lateinischen Schrift zurück oder legt sie fest.<br/>            Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden sollte.<br/>            Lese/Schreib [`IFontData`](/slides/python-net/de/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/de/aspose.slides/baseportionformat/east_asian_font/) | Gibt die Informationen zur ostasiatischen Schrift zurück oder legt sie fest.<br/>            Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden sollte.<br/>            Lese/Schreib [`IFontData`](/slides/python-net/de/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/de/aspose.slides/baseportionformat/complex_script_font/) | Gibt die Informationen zur komplexen Skript-Schrift zurück oder legt sie fest.<br/>            Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden sollte.<br/>            Lese/Schreib [`IFontData`](/slides/python-net/de/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/de/aspose.slides/baseportionformat/symbol_font/) | Gibt die Informationen zur symbolischen Schrift zurück oder legt sie fest.<br/>            Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden sollte.<br/>            Lese/Schreib [`IFontData`](/slides/python-net/de/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/de/aspose.slides/baseportionformat/escapement/) | Gibt den Hoch- oder Tiefgestellt-Text zurück oder legt ihn fest.<br/>            Wert von -100 % (Tiefgestellt) bis 100 % (Hochgestellt).<br/>            **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte.<br/>            Lese/Schreib **float**. |
| [`kerning_minimal_size`](/slides/python-net/de/aspose.slides/baseportionformat/kerning_minimal_size/) | Gibt die minimale Schriftgröße zurück, ab der Kerning aktiviert werden soll.<br/>            **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte.<br/>            Lese/Schreib **float**. |
| [`language_id`](/slides/python-net/de/aspose.slides/baseportionformat/language_id/) | Gibt die Id einer Korrektursprache zurück oder legt sie fest. Wird zum Prüfen von Rechtschreibung und Grammatik verwendet.<br/>            Lese/Schreib **str**. |
| [`alternative_language_id`](/slides/python-net/de/aspose.slides/baseportionformat/alternative_language_id/) | Gibt die Id einer alternativen Sprache zurück oder legt sie fest.<br/>            Lese/Schreib **str**. |
| [`spacing`](/slides/python-net/de/aspose.slides/baseportionformat/spacing/) | Gibt die Erhöhung des Zeichenabstands zurück oder legt sie fest.<br/>            **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte.<br/>            Lese/Schreib **float**. |
| [`spell_check`](/slides/python-net/de/aspose.slides/baseportionformat/spell_check/) | Gibt an, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist, oder legt den Wert fest.<br/>            Ist diese Eigenschaft auf false gesetzt, werden Rechtschreibprüfungen für Textelemente unterdrückt.<br/>            Ist sie auf true gesetzt, ist die Rechtschreibprüfung erlaubt.<br/>            Standardwert ist `false`. |
| [`slide`](/slides/python-net/de/aspose.slides/baseportionformat/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/baseportionformat/presentation/) |  |

### Siehe auch
* Klasse [`BasePortionFormat`](/slides/python-net/de/aspose.slides/baseportionformat)
* Klasse [`PVIObject`](/slides/python-net/de/aspose.slides/pviobject)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)