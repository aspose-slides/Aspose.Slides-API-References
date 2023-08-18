---
title: ParagraphFormat
second_title: Aspose.Slides für .NET-API-Referenz
description: Diese Klasse enthält die Absatzformatierungseigenschaften. nicht wieIParagraphFormatEffectiveData./iparagraphformateffectivedata  alle Eigenschaften dieser Klasse sind beschreibbar.
type: docs
weight: 8610
url: /de/aspose.slides/paragraphformat/
---
## ParagraphFormat class

Diese Klasse enthält die Absatzformatierungseigenschaften. nicht wie[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) , alle Eigenschaften dieser Klasse sind beschreibbar.

```csharp
public class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initialisiert eine neue Instanz von[`ParagraphFormat`](../paragraphformat) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben[`TextAlignment`](../textalignment) . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPPresentationComponent-Schnittstelle. Schreibgeschützt[`IPresentationComponent`](../ipresentationcomponent) . |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Gibt die Standardtabellengröße ohne Vererbung zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Legt fest, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Gibt eine Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben[`FontAlignment`](../fontalignment) . |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Bestimmt, ob die hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Gibt den Erstzeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder legt ihn fest. Hanging Indent kann mit negativen Werten definiert werden. Read/writeSingle . |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Legt fest, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/SchreibenSingle . |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/SchreibenSingle . |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Legt fest, ob in einem Absatz die Schreibweise von rechts nach links verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punkt an Größe. Lesen/SchreibenSingle . |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punkt an Größe. Lesen/SchreibenSingle . |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder legt ihn fest. Positive Werte bedeuten Prozent, negative - Größe in Punkten. Keine Vererbung angewendet. Lesen/SchreibenSingle . |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Gibt Tabellierungen eines Absatzes zurück. Keine Vererbung angewendet. Schreibgeschützt[`ITabCollection`](../itabcollection) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit angegebenem Objekt. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Ruft effektive Absatzformatierungsdaten mit angewendeter Vererbung ab. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt Hash-Code zurück. |

### Bemerkungen

Diese Klasse wird verwendet, um die für den jeweiligen Absatz definierten Absatzformatierungseigenschaften zurückzugeben und zu bearbeiten. Dies bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die "undefiniert" bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich geerbter Werte zu erhalten, müssen Sie verwenden[`GetEffective`](./geteffective) Methode , die a zurückgibt[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) Beispiel.

### Siehe auch

* class [PVIObject](../pviobject)
* interface [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interface [IParagraphFormat](../iparagraphformat)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
