---
title: IParagraphFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Diese Klasse enthält die Absatzformatierungseigenschaften. Im Gegensatz zu IParagraphFormatEffectiveData./iparagraphformateffectivedata sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 6610
url: /de/aspose.slides/iparagraphformat/
---
## IParagraphFormat Schnittstelle

This class contains the paragraph formatting properties. Unlike [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), all properties of this class are writeable.

```csharp
public interface IParagraphFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. Lesen/Schreiben [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Gibt das Aufzählungsformat des Absatzes zurück. Nur-Lesen [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Gibt das Standardabschnittsformat eines Absatzes zurück. Keine Vererbung angewendet. Nur-Lesen [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Gibt die Standard-Tabulationsgröße ohne Vererbung zurück oder setzt sie. Lesen/Schreiben Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Gibt die Tiefe des Absatzes zurück oder setzt sie. Der Wert 0 bedeutet undefinierten Wert. Lesen/Schreiben Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Bestimmt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Gibt die Schriftartenausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. Lesen/Schreiben [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Bestimmt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Gibt den ersten Zeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder setzt ihn. Der hängende Einzug kann mit negativen Werten definiert werden. Lesen/Schreiben Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. Lesen/Schreiben Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. Lesen/Schreiben Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Bestimmt, ob rechts-nach-links-Schreiben in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder setzt ihn. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/Schreiben Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder setzt ihn. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/Schreiben Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder setzt ihn. Positiver Wert bedeutet Prozentsatz, negativer - Größe in Punkten. Keine Vererbung angewendet. Lesen/Schreiben Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Gibt die Tabulationen eines Absatzes zurück. Keine Vererbung angewendet. Nur-Lesen [`ITabCollection`](../itabcollection). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Ruft die effektiven Absatzformatierungsdaten ab, bei denen die Vererbung angewendet wurde. |

### Hinweise

Diese Klasse wird verwendet, um Absatzformatierungseigenschaften zurückzugeben und zu manipulieren, die für den jeweiligen Absatz definiert sind. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, so dass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die Methode [`GetEffective`](./geteffective) verwenden, die eine [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)-Instanz zurückgibt.

### Siehe auch

* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->