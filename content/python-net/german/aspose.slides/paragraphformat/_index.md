---
title: ParagraphFormat class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/paragraphformat/
---
## ParagraphFormat Klasse

Diese Klasse enthält die Absatzeigenschafts-Formatierungs-Eigenschaften. Im Gegensatz zu [`IParagraphFormatEffectiveData`](/slides/python-net/de/aspose.slides/iparagraphformateffectivedata) sind alle Eigenschaften dieser Klasse beschreibbar.

**Inheritance:**[`ParagraphFormat`](/slides/python-net/de/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/de/aspose.slides/pviobject)

Der ParagraphFormat-Typ stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides/paragraphformat/__init__/#) | Initialisiert eine neue Instanz der [`ParagraphFormat`](/slides/python-net/de/aspose.slides/paragraphformat) Klasse. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`alignment`](/slides/python-net/de/aspose.slides/paragraphformat/alignment/) | Gibt die Textausrichtung in einem Absatz zurück oder legt sie fest, ohne Vererbung.<br/>            Lesen/Schreiben [`TextAlignment`](/slides/python-net/de/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/de/aspose.slides/paragraphformat/space_within/) | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder legt ihn fest. Ein positiver Wert bedeutet Prozentsatz, ein negativer – Größe in Punkt. Keine Vererbung angewendet.<br/>            Lesen/Schreiben **float**. |
| [`space_before`](/slides/python-net/de/aspose.slides/paragraphformat/space_before/) | Gibt den Abstand vor der ersten Zeile in einem Absatz zurück oder legt ihn fest, ohne Vererbung.<br/>            Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll.<br/>            Ein negativer Wert gibt die Größe des Leerraums in Punkt an.<br/>            Lesen/Schreiben **float**. |
| [`space_after`](/slides/python-net/de/aspose.slides/paragraphformat/space_after/) | Gibt den Abstand nach der letzten Zeile in einem Absatz zurück oder legt ihn fest, ohne Vererbung.<br/>            Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll.<br/>            Ein negativer Wert gibt die Größe des Leerraums in Punkt an.<br/>            Lesen/Schreiben **float**. |
| [`east_asian_line_break`](/slides/python-net/de/aspose.slides/paragraphformat/east_asian_line_break/) | Bestimmt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/de/aspose.slides/paragraphformat/right_to_left/) | Bestimmt, ob Rechts-zu-Links-Schreiben in einem Absatz verwendet wird. Keine Vererbung angewendet.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/de/aspose.slides/paragraphformat/latin_line_break/) | Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/de/aspose.slides/paragraphformat/hanging_punctuation/) | Bestimmt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/de/aspose.slides/paragraphformat/margin_left/) | Gibt den linken Rand in einem Absatz zurück oder legt ihn fest, ohne Vererbung.<br/>            Lesen/Schreiben **float**. |
| [`margin_right`](/slides/python-net/de/aspose.slides/paragraphformat/margin_right/) | Gibt den rechten Rand in einem Absatz zurück oder legt ihn fest, ohne Vererbung.<br/>            Lesen/Schreiben **float**. |
| [`indent`](/slides/python-net/de/aspose.slides/paragraphformat/indent/) | Gibt den ersten Zeileneinzug/Hängenden Einzug des Absatzes zurück oder legt ihn fest, ohne Vererbung. Hängender Einzug kann mit negativen Werten definiert werden.<br/>            Lesen/Schreiben **float**. |
| [`default_tab_size`](/slides/python-net/de/aspose.slides/paragraphformat/default_tab_size/) | Gibt die Standard-Tabulatorgröße zurück oder legt sie fest, ohne Vererbung.<br/>            Lesen/Schreiben **float**. |
| [`tabs`](/slides/python-net/de/aspose.slides/paragraphformat/tabs/) | Gibt die Tabulatoren eines Absatzes zurück. Keine Vererbung angewendet.<br/>            Nur lesen [`ITabCollection`](/slides/python-net/de/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/de/aspose.slides/paragraphformat/font_alignment/) | Gibt die Schriftartausrichtung in einem Absatz zurück oder legt sie fest, ohne Vererbung.<br/>            Lesen/Schreiben [`FontAlignment`](/slides/python-net/de/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/de/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/de/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/de/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/de/aspose.slides/paragraphformat/default_portion_format/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/de/aspose.slides/paragraphformat/get_effective/#) | Ermittelt die effektiven Absatzformatierungsdaten mit angewandter Vererbung. |

### Hinweise

Diese Klasse wird verwendet, um Absatzformatierungseigenschaften zurückzugeben und zu manipulieren, die für den jeweiligen Absatz definiert sind. Das bedeutet, dass bei der Abfrage von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die Methode [`ParagraphFormat.get_effective`](/slides/python-net/de/aspose.slides/paragraphformat/get_effective) verwenden, die eine [`IParagraphFormatEffectiveData`](/slides/python-net/de/aspose.slides/iparagraphformateffectivedata)-Instanz zurückgibt.

### Siehe auch
* Klasse [`IParagraphFormatEffectiveData`](/slides/python-net/de/aspose.slides/iparagraphformateffectivedata)
* Klasse [`ParagraphFormat`](/slides/python-net/de/aspose.slides/paragraphformat)
* Klasse [`PVIObject`](/slides/python-net/de/aspose.slides/pviobject)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)