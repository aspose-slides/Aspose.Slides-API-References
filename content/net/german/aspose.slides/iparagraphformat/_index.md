---
title: IParagraphFormat
second_title: Aspose.Slides für .NET-API-Referenz
description: Diese Klasse enthält die Absatzformatierungseigenschaften. nicht wieIParagraphFormatEffectiveData./iparagraphformateffectivedata  alle Eigenschaften dieser Klasse sind beschreibbar.
type: docs
weight: 6060
url: /de/aspose.slides/iparagraphformat/
---
## IParagraphFormat interface

Diese Klasse enthält die Absatzformatierungseigenschaften. nicht wie[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) , alle Eigenschaften dieser Klasse sind beschreibbar.

```csharp
public interface IParagraphFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben[`TextAlignment`](../textalignment) . |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Gibt das Aufzählungsformat des Absatzes zurück. Schreibgeschützt[`IBulletFormat`](../ibulletformat) . |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Gibt das Standardteilformat eines Absatzes zurück. Keine Vererbung angewendet. Schreibgeschützt[`IPortionFormat`](../iportionformat) . |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Gibt die Standardtabellengröße ohne Vererbung zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Gibt die Absatztiefe zurück oder legt sie fest. Wert 0 bedeutet undefinierter Wert. Lesen/SchreibenInt16 . |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Legt fest, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Gibt eine Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben[`FontAlignment`](../fontalignment) . |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Bestimmt, ob die hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Gibt den Erstzeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder legt ihn fest. Hanging Indent kann mit negativen Werten definiert werden. Read/writeSingle . |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Legt fest, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/SchreibenSingle . |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/SchreibenSingle . |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Legt fest, ob in einem Absatz die Schreibweise von rechts nach links verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punkt an Größe. Lesen/SchreibenSingle . |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punkt an Größe. Lesen/SchreibenSingle . |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder legt ihn fest. Positive Werte bedeuten Prozent, negative - Größe in Punkten. Keine Vererbung angewendet. Lesen/SchreibenSingle . |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Gibt Tabellierungen eines Absatzes zurück. Keine Vererbung angewendet. Schreibgeschützt[`ITabCollection`](../itabcollection) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Ruft effektive Absatzformatierungsdaten mit angewendeter Vererbung ab. |

### Bemerkungen

Diese Klasse wird verwendet, um die für den jeweiligen Absatz definierten Absatzformatierungseigenschaften zurückzugeben und zu bearbeiten. Dies bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die "undefiniert" bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich geerbter Werte zu erhalten, müssen Sie verwenden[`GetEffective`](./geteffective) Methode , die a zurückgibt[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) Beispiel.

### Siehe auch

* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
