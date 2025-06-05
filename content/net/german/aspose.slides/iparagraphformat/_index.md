---  
title: IParagraphFormat
second_title: Aspose.Slides für .NET API-Referenz  
description: Diese Klasse enthält die Eigenschaften der Absatzformatierung. Im Gegensatz zu IParagraphFormatEffectiveData../iparagraphformateffectivedata sind alle Eigenschaften dieser Klasse beschreibbar.
type: docs
weight: 6390  
url: /de/aspose.slides/iparagraphformat/
---  

## IParagraphFormat-Schnittstelle  

Diese Klasse enthält die Eigenschaften der Absatzformatierung. Im Gegensatz zu [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) sind alle Eigenschaften dieser Klasse beschreibbar.  

```csharp  
public interface IParagraphFormat  
```  

## Eigenschaften  

| Name | Beschreibung |  
| --- | --- |  
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder setzt diese. Lesen/Schreiben [`TextAlignment`](../textalignment). |  
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Gibt das Aufzählungsformat des Absatzes zurück. Nur-Lesen [`IBulletFormat`](../ibulletformat). |  
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Gibt das standardmäßige Portionsformat eines Absatzes zurück. Keine Vererbung angewendet. Nur-Lesen [`IPortionFormat`](../iportionformat). |  
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Gibt die standardmäßige Tabulatorgröße ohne Vererbung zurück oder setzt diese. Lesen/Schreiben Single. |  
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Gibt die Tiefe des Absatzes zurück oder setzt diese. Wert 0 bedeutet undefinierter Wert. Lesen/Schreiben Int16. |  
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Bestimmt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |  
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Gibt eine Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder setzt diese. Lesen/Schreiben [`FontAlignment`](../fontalignment). |  
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Bestimmt, ob die hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |  
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Gibt den ersten Einzug/hängenden Einzug des Absatzes ohne Vererbung zurück oder setzt diesen. Hängender Einzug kann mit negativen Werten definiert werden. Lesen/Schreiben Single. |  
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |  
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder setzt diesen. Lesen/Schreiben Single. |  
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder setzt diesen. Lesen/Schreiben Single. |  
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Bestimmt, ob die Schreibeichtung von rechts nach links in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |  
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Gibt die Menge des Abstands nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder setzt diese. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/Schreiben Single. |  
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Gibt die Menge des Abstands vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder setzt diese. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/Schreiben Single. |  
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Gibt die Menge des Abstands zwischen Basislinien in einem Absatz zurück oder setzt diese. Positiver Wert bedeutet Prozentsatz, negativ - Größe in Punkten. Keine Vererbung angewendet. Lesen/Schreiben Single. |  
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Gibt die Tabulatoren eines Absatzes zurück. Keine Vererbung angewendet. Nur-Lesen [`ITabCollection`](../itabcollection). |  

## Methoden  

| Name | Beschreibung |  
| --- | --- |  
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Erhält die effektiven Absatzformatierungsdaten mit der angewendeten Vererbung. |  

### Anmerkungen  

Diese Klasse wird verwendet, um die Eigenschaften der Absatzformatierung zurückzugeben und zu manipulieren, die für den bestimmten Absatz definiert sind. Das bedeutet, dass keine Vererbung angewendet wird, wenn Werte abgerufen werden, sodass in den meisten Fällen Werte zurückgegeben werden, die "undefiniert" bedeuten.  

Um die effektiven Formatierungsparameterwerte einschließlich der vererbten Werte zu erhalten, müssen Sie die Methode [`GetEffective`](./geteffective) verwenden, die eine Instanz von [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) zurückgibt.  

### Siehe Auch  

* Namespace [Aspose.Slides](../../aspose.slides)  
* Assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  