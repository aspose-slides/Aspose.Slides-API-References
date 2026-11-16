---
title: ParagraphFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Diese Klasse enthält die Absatzformatierungseigenschaften. Im Gegensatz zu IParagraphFormatEffectiveData./iparagraphformateffectivedata sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 9330
url: /de/aspose.slides/paragraphformat/
---
## ParagraphFormat Klasse

Diese Klasse enthält die Absatzformatierungseigenschaften. Im Gegensatz zu [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

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
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPresentationComponent-Schnittstelle. Nur-Lesen [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Gibt die Standard-Tabulatorgröße ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Bestimmt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Gibt die Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Bestimmt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Gibt den ersten Zeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder legt ihn fest. Der hängende Einzug kann mit negativen Werten definiert werden. Lesen/Schreiben Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Bestimmt, ob Rechts-nach-Links-Schreiben in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/Schreiben Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/Schreiben Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder legt ihn fest. Ein positiver Wert bedeutet Prozent, ein negativer – Größe in Punkten. Keine Vererbung angewendet. Lesen/Schreiben Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Gibt die Tabulatoren eines Absatzes zurück. Keine Vererbung angewendet. Nur-Lesen [`ITabCollection`](../itabcollection). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Ruft effektive Absatzformatierungsdaten ab, wobei die Vererbung angewendet wird. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Anmerkungen

Diese Klasse wird verwendet, um Absatzformatierungseigenschaften zurückzugeben und zu manipulieren, die für den jeweiligen Absatz definiert sind. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich geerbter Werte zu erhalten, müssen Sie die [`GetEffective`](./geteffective)-Methode verwenden, die eine [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)-Instanz zurückgibt.

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* Schnittstelle [IParagraphFormat](../iparagraphformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->