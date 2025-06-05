---
title: ParagraphFormat
second_title: Aspose.Slides für .NET API Referenz
description: Diese Klasse enthält die Eigenschaften zur Absatzformatierung. Im Gegensatz zu IParagraphFormatEffectiveData sind alle Eigenschaften dieser Klasse beschreibbar.
type: docs
weight: 9040
url: /de/aspose.slides/paragraphformat/
---

## ParagraphFormat-Klasse

Diese Klasse enthält die Eigenschaften zur Absatzformatierung. Im Gegensatz zu [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) sind alle Eigenschaften dieser Klasse beschreibbar.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initialisiert eine neue Instanz der [`ParagraphFormat`](../paragraphformat) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder setzt diese. Lese-/Schreibzugriff auf [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IPresentationComponent-Schnittstelle. Nur Lesezugriff auf [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Gibt die standardmäßige Tabulatorgröße ohne Vererbung zurück oder setzt diese. Lese-/Schreibzugriff auf Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Bestimmt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine angewandte Vererbung. Lese-/Schreibzugriff auf [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Gibt eine Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder setzt diese. Lese-/Schreibzugriff auf [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Bestimmt, ob die hängende Interpunktion in einem Absatz verwendet wird. Keine angewandte Vererbung. Lese-/Schreibzugriff auf [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Gibt den ersten Zeilenabstand/Hängenden Einzug eines Absatzes ohne Vererbung zurück oder setzt diesen. Hängender Einzug kann mit negativen Werten definiert werden. Lese-/Schreibzugriff auf Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine angewandte Vererbung. Lese-/Schreibzugriff auf [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder setzt diesen. Lese-/Schreibzugriff auf Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder setzt diesen. Lese-/Schreibzugriff auf Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Bestimmt, ob die Schreibrichtung von rechts nach links in einem Absatz verwendet wird. Keine angewandte Vererbung. Lese-/Schreibzugriff auf [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder setzt diesen. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben sollte. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lese-/Schreibzugriff auf Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder setzt diesen. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben sollte. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lese-/Schreibzugriff auf Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Gibt den Abstand zwischen der Grundlinie in einem Absatz zurück oder setzt diesen. Positiver Wert bedeutet Prozentsatz, negativer - Größe in Punkten. Keine angewandte Vererbung. Lese-/Schreibzugriff auf Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Gibt die Tabulatoren eines Absatzes zurück. Keine angewandte Vererbung. Nur Lesezugriff auf [`ITabCollection`](../itabcollection). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Holt die effektiven Daten zur Absatzformatierung mit angewandter Vererbung. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Anmerkungen

Diese Klasse wird verwendet, um die Eigenschaften zur Absatzformatierung zurückzugeben und zu manipulieren, die für den bestimmten Absatz definiert sind. Das bedeutet, dass keine Vererbung angewandt wird, wenn Werte abgerufen werden, sodass Sie in den meisten Fällen Werte erhalten, die "nicht definiert" bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich der geerbten zu erhalten, müssen Sie die Methode [`GetEffective`](./geteffective) verwenden, die eine Instanz von [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) zurückgibt.

### Siehe Auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* Schnittstelle [IParagraphFormat](../iparagraphformat)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->