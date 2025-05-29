---
title: IParagraphFormat
second_title: Aspose.Slides für .NET API Referenz
description: Diese Klasse enthält die Eigenschaften der Absatzformatierung. Im Gegensatz zu IParagraphFormatEffectiveData sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 6390
url: /de/aspose.slides/iparagraphformat/
---

## IParagraphFormat-Schnittstelle

Diese Klasse enthält die Eigenschaften der Absatzformatierung. Im Gegensatz zu [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

```csharp
public interface IParagraphFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. Lese-/Schreibzugriff [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Gibt das Aufzählungsformat des Absatzes zurück. Lesen nur [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Gibt das Standardformat eines Absatzteils zurück. Keine angewandte Vererbung. Lesen nur [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Gibt die Standardtabulatorgröße ohne Vererbung zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Gibt die Tiefe des Absatzes zurück oder setzt sie. Wert 0 bedeutet undefinierten Wert. Lese-/Schreibzugriff Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Bestimmt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine angewandte Vererbung. Lese-/Schreibzugriff [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Gibt eine Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder setzt sie. Lese-/Schreibzugriff [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Bestimmt, ob die hängende Interpunktion in einem Absatz verwendet wird. Keine angewandte Vererbung. Lese-/Schreibzugriff [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Gibt den Einzug der ersten Zeile/des hängenden Einzugs des Absatzes ohne Vererbung zurück oder setzt ihn. Hängender Einzug kann mit negativen Werten definiert werden. Lese-/Schreibzugriff Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine angewandte Vererbung. Lese-/Schreibzugriff [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. Lese-/Schreibzugriff Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder setzt ihn. Lese-/Schreibzugriff Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Bestimmt, ob die Schreibrichtung von rechts nach links in einem Absatz verwendet wird. Keine angewandte Vererbung. Lese-/Schreibzugriff [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Gibt die Menge an Platz nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder setzt sie. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der weiße Raum einnehmen sollte. Ein negativer Wert gibt die Größe des weißen Raums in Punktgröße an. Lese-/Schreibzugriff Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Gibt die Menge an Platz vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder setzt sie. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der weiße Raum einnehmen sollte. Ein negativer Wert gibt die Größe des weißen Raums in Punktgröße an. Lese-/Schreibzugriff Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Gibt die Menge an Platz zwischen den Grundlinien in einem Absatz zurück oder setzt sie. Positiver Wert bedeutet Prozentsatz, negativer - Größe in Punkten. Keine angewandte Vererbung. Lese-/Schreibzugriff Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Gibt die Tabulatoren eines Absatzes zurück. Keine angewandte Vererbung. Lesen nur [`ITabCollection`](../itabcollection). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Holt die effektiven Absatzformatierungsdaten mit der angewandten Vererbung. |

### Anmerkungen

Diese Klasse wird verwendet, um die für den bestimmten Absatz definierten Eigenschaften der Absatzformatierung zurückzugeben und zu manipulieren. Das bedeutet, dass keine Vererbung angewandt wird, wenn Werte abgerufen werden, sodass in den meisten Fällen Werte zurückgegeben werden, die "undefiniert" bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich der vererbten zu erhalten, müssen Sie die Methode [`GetEffective`](./geteffective) verwenden, die eine Instanz von [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) zurückgibt.

### Siehe auch

* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->