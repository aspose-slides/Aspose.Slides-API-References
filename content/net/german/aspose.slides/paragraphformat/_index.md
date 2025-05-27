---
title: ParagraphFormat
second_title: Aspose.Slides für .NET API-Referenz
description: Diese Klasse enthält die Eigenschaften der Absatzformatierung. Im Gegensatz zu IParagraphFormatEffectiveData./iparagraphformateffectivedata sind alle Eigenschaften dieser Klasse beschreibbar.
type: docs
weight: 9040
url: /de/aspose.slides/paragraphformat/
---

## ParagraphFormat-Klasse

Diese Klasse enthält die Eigenschaften der Absatzformatierung. Im Gegensatz zu [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) sind alle Eigenschaften dieser Klasse beschreibbar.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initialisiert eine neue Instanz der [`ParagraphFormat`](../paragraphformat)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/ Schreiben [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IPresentationComponent-Schnittstelle. Nur lesbar [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Gibt die Standard-Tabulatorgröße ohne Vererbung zurück oder legt sie fest. Lesen/ Schreiben Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Bestimmt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/ Schreiben [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Gibt die Schriftartenausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/ Schreiben [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Bestimmt, ob die hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/ Schreiben [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Gibt den ersten Zeilenrückstand/ hängenden Rückstand eines Absatzes ohne Vererbung zurück oder legt ihn fest. Der hängende Rückstand kann mit negativen Werten definiert werden. Lesen/ Schreiben Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/ Schreiben [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/ Schreiben Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/ Schreiben Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Bestimmt, ob die Schreibrichtung von rechts nach links in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/ Schreiben [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Gibt den Betrag des Abstands nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt an, welcher Prozentsatz der Schriftgröße der Leerraum betragen sollte. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/ Schreiben Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Gibt den Betrag des Abstands vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt an, welcher Prozentsatz der Schriftgröße der Leerraum betragen sollte. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/ Schreiben Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Gibt den Betrag des Abstands zwischen Grundlinien in einem Absatz zurück oder legt ihn fest. Ein positiver Wert bedeutet Prozentsatz, negativ - Größe in Punkten. Keine Vererbung angewendet. Lesen/ Schreiben Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Gibt die Tabulatoren eines Absatzes zurück. Keine Vererbung angewendet. Nur lesbar [`ITabCollection`](../itabcollection). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Ruft die effektiven Absatzformatierungsdaten mit angewendeter Vererbung ab. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Anmerkungen

Diese Klasse wird verwendet, um die für den bestimmten Absatz definierten Eigenschaften der Absatzformatierung zurückzugeben und zu manipulieren. Das bedeutet, dass keine Vererbung angewendet wird, wenn Werte abgerufen werden, sodass Sie in den meisten Fällen Werte erhalten, die "nicht definiert" bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich der geerbten abzurufen, müssen Sie die Methode [`GetEffective`](./geteffective) verwenden, die eine Instanz von [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) zurückgibt.

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* Schnittstelle [IParagraphFormat](../iparagraphformat)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assemblierung [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->