---
title: IParagraphFormat class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iparagraphformat/
---
## IParagraphFormat Klasse

Diese Klasse enthält die Absatzformatierungseigenschaften. Im Gegensatz zu [`IParagraphFormatEffectiveData`](/slides/python-net/de/aspose.slides/iparagraphformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

Der IParagraphFormat-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`bullet`](/slides/python-net/de/aspose.slides/iparagraphformat/bullet/) | Gibt das Aufzählungsformat des Absatzes zurück.<br/>            Nur lesbar [`IBulletFormat`](/slides/python-net/de/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/de/aspose.slides/iparagraphformat/depth/) | Gibt die Tiefe des Absatzes zurück oder legt sie fest.<br/>            Der Wert 0 bedeutet undefinierten Wert.<br/>            Lesen/Schreiben **int**. |
| [`alignment`](/slides/python-net/de/aspose.slides/iparagraphformat/alignment/) | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest.<br/>            Lesen/Schreiben [`TextAlignment`](/slides/python-net/de/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/de/aspose.slides/iparagraphformat/space_within/) | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder legt ihn fest. Ein positiver Wert bedeutet Prozentsatz, ein negativer – Größe in Punkt. Keine Vererbung angewendet.<br/>            Lesen/Schreiben **float**. |
| [`space_before`](/slides/python-net/de/aspose.slides/iparagraphformat/space_before/) | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest.<br/>            Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll.<br/>            Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an.<br/>            Lesen/Schreiben **float**. |
| [`space_after`](/slides/python-net/de/aspose.slides/iparagraphformat/space_after/) | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest.<br/>            Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll.<br/>            Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an.<br/>            Lesen/Schreiben **float**. |
| [`east_asian_line_break`](/slides/python-net/de/aspose.slides/iparagraphformat/east_asian_line_break/) | Bestimmt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/de/aspose.slides/iparagraphformat/right_to_left/) | Bestimmt, ob die Schreibrichtung von rechts nach links in einem Absatz verwendet wird. Keine Vererbung angewendet.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/de/aspose.slides/iparagraphformat/latin_line_break/) | Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/de/aspose.slides/iparagraphformat/hanging_punctuation/) | Bestimmt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/de/aspose.slides/iparagraphformat/margin_left/) | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`margin_right`](/slides/python-net/de/aspose.slides/iparagraphformat/margin_right/) | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`indent`](/slides/python-net/de/aspose.slides/iparagraphformat/indent/) | Gibt den ersten Zeileneinzug/hängenden Einzug des Absatzes ohne Vererbung zurück oder legt ihn fest. Der hängende Einzug kann mit negativen Werten definiert werden.<br/>            Lesen/Schreiben **float**. |
| [`default_tab_size`](/slides/python-net/de/aspose.slides/iparagraphformat/default_tab_size/) | Gibt die Standardtabulationsgröße ohne Vererbung zurück oder legt sie fest.<br/>            Lesen/Schreiben **float**. |
| [`tabs`](/slides/python-net/de/aspose.slides/iparagraphformat/tabs/) | Gibt die Tabulatoren eines Absatzes zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`ITabCollection`](/slides/python-net/de/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/de/aspose.slides/iparagraphformat/font_alignment/) | Gibt die Schriftausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest.<br/>            Lesen/Schreiben [`FontAlignment`](/slides/python-net/de/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/de/aspose.slides/iparagraphformat/default_portion_format/) | Gibt das Standardabschnittsformat eines Absatzes zurück. Keine Vererbung angewendet.<br/>            Nur lesbar [`IPortionFormat`](/slides/python-net/de/aspose.slides/iportionformat). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/de/aspose.slides/iparagraphformat/get_effective/#) | Ruft die wirksamen Absatzformatierungsdaten mit angewendeter Vererbung ab. |

### Bemerkungen

Diese Klasse wird verwendet, um die für einen bestimmten Absatz definierten Absatzformatierungseigenschaften zurückzugeben und zu manipulieren. Das bedeutet, dass keine Vererbung angewendet wird, wenn Werte abgerufen werden, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die wirksamen Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die Methode [`IParagraphFormat.get_effective`](/slides/python-net/de/aspose.slides/iparagraphformat/get_effective) verwenden, die eine [`IParagraphFormatEffectiveData`](/slides/python-net/de/aspose.slides/iparagraphformateffectivedata)-Instanz zurückgibt.

### Siehe auch
* Klasse [`IParagraphFormatEffectiveData`](/slides/python-net/de/aspose.slides/iparagraphformateffectivedata)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)