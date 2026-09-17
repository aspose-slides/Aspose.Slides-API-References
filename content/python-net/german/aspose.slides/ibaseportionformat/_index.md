---
title: IBasePortionFormat class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat Klasse

Diese Klasse enthält die Formatierungseigenschaften für Textabschnitte. Im Gegensatz zu [`IPortionFormatEffectiveData`](/slides/python-net/de/aspose.slides/iportionformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

Der Typ IBasePortionFormat stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`line_format`](/slides/python-net/de/aspose.slides/ibaseportionformat/line_format/) | Gibt die LineFormat-Eigenschaften für Textumriss zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/ibaseportionformat/fill_format/) | Gibt die FillFormat-Eigenschaften für Text zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/ibaseportionformat/effect_format/) | Gibt die EffectFormat-Eigenschaften für Text zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/de/aspose.slides/ibaseportionformat/highlight_color/) | Gibt die für die Hervorhebung von Text verwendete Farbe zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`IColorFormat`](/slides/python-net/de/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/de/aspose.slides/ibaseportionformat/underline_line_format/) | Gibt die LineFormat-Eigenschaften für die Kontur der Unterstreichung zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/de/aspose.slides/ibaseportionformat/underline_fill_format/) | Gibt die FillFormat-Eigenschaften für die Unterstreichungslinie zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/de/aspose.slides/ibaseportionformat/font_bold/) | Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/de/aspose.slides/ibaseportionformat/font_italic/) | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/de/aspose.slides/ibaseportionformat/kumimoji/) | Bestimmt, ob die Zahlen das vertikale Textlayout ostasiatischer Sprachen ignorieren sollen. Keine Vererbung angewendet.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/de/aspose.slides/ibaseportionformat/normalise_height/) | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/de/aspose.slides/ibaseportionformat/proof_disabled/) | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/de/aspose.slides/ibaseportionformat/font_underline/) | Gibt die Art der Unterstreichung zurück oder legt sie fest. Keine Vererbung angewendet.<br/>            Lese/Schreib [`TextUnderlineType`](/slides/python-net/de/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/de/aspose.slides/ibaseportionformat/text_cap_type/) | Gibt die Art der Groß-/Kleinschreibung zurück oder legt sie fest. Keine Vererbung angewendet.<br/>            Lese/Schreib [`TextCapType`](/slides/python-net/de/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/de/aspose.slides/ibaseportionformat/strikethrough_type/) | Gibt die Art des Durchstreichens zurück oder legt sie fest. Keine Vererbung angewendet.<br/>            Lese/Schreib [`TextStrikethroughType`](/slides/python-net/de/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/de/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/de/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/de/aspose.slides/ibaseportionformat/font_height/) | Gibt die Schriftgröße eines Abschnitts zurück oder legt sie fest.<br/>            **float.NaN** bedeutet, dass die Größe undefiniert ist und vom Master geerbt werden soll.<br/>            Lese/Schreib **float**. |
| [`latin_font`](/slides/python-net/de/aspose.slides/ibaseportionformat/latin_font/) | Gibt die lateinischen Schriftinformationen zurück oder legt sie fest.<br/>            Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll.<br/>            Lese/Schreib [`IFontData`](/slides/python-net/de/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/de/aspose.slides/ibaseportionformat/east_asian_font/) | Gibt die ostasiatischen Schriftinformationen zurück oder legt sie fest.<br/>            Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll.<br/>            Lese/Schreib [`IFontData`](/slides/python-net/de/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/de/aspose.slides/ibaseportionformat/complex_script_font/) | Gibt die komplexen Skript-Schriftinformationen zurück oder legt sie fest.<br/>            Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll.<br/>            Lese/Schreib [`IFontData`](/slides/python-net/de/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/de/aspose.slides/ibaseportionformat/symbol_font/) | Gibt die symbolischen Schriftinformationen zurück oder legt sie fest.<br/>            Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden soll.<br/>            Lese/Schreib [`IFontData`](/slides/python-net/de/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/de/aspose.slides/ibaseportionformat/escapement/) | Gibt den hoch- oder tiefgestellten Text zurück oder legt ihn fest.<br/>            Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt).<br/>            **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll.<br/>            Lese/Schreib **float**. |
| [`kerning_minimal_size`](/slides/python-net/de/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Gibt die minimale Schriftgröße zurück, ab der Kerning aktiviert werden soll, oder legt sie fest.<br/>            **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll.<br/>            Lese/Schreib **float**. |
| [`language_id`](/slides/python-net/de/aspose.slides/ibaseportionformat/language_id/) | Gibt die Id einer Korrektursprache zurück oder legt sie fest. Wird für Rechtschreib- und Grammatikprüfung verwendet.<br/>            Lese/Schreib **str**. |
| [`alternative_language_id`](/slides/python-net/de/aspose.slides/ibaseportionformat/alternative_language_id/) | Gibt die Id einer alternativen Sprache zurück oder legt sie fest.<br/>            Lese/Schreib **str**. |
| [`spacing`](/slides/python-net/de/aspose.slides/ibaseportionformat/spacing/) | Gibt den Inkrementwert für den Interzeichenabstand zurück oder legt ihn fest.<br/>            **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll.<br/>            Lese/Schreib **float**. |
| [`spell_check`](/slides/python-net/de/aspose.slides/ibaseportionformat/spell_check/) | Gibt einen Wert zurück oder legt ihn fest, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist.<br/>            Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt.<br/>            Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt.<br/>            Der Standardwert ist `false`. |

### Anmerkungen

Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Formatierungseigenschaften von Text zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die wirksamen Formatierungsparameter einschließlich vererbter Werte zu erhalten, müssen Sie die [`IPortionFormat.get_effective`](/slides/python-net/de/aspose.slides/iportionformat/get_effective)-Methode verwenden, die eine [`IPortionFormatEffectiveData`](/slides/python-net/de/aspose.slides/iportionformateffectivedata)-Instanz zurückgibt.

### Siehe auch
* Klasse [`IPortionFormatEffectiveData`](/slides/python-net/de/aspose.slides/iportionformateffectivedata)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)