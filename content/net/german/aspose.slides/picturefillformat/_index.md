---
title: PictureFillFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt einen Bildfüllstil dar.
type: docs
weight: 9410
url: /de/aspose.slides/picturefillformat/
---
## PictureFillFormat Klasse

Stellt einen Bildfüllstil dar.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPresentationComponent-Schnittstelle. Nur-Lesen [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Gibt die prozentuale Anzahl der realen Bildhöhe zurück, die am unteren Rand des Bildes abgeschnitten wird, oder legt sie fest. Lese/Schreib Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Gibt die prozentuale Anzahl der realen Bildbreite zurück, die am linken Rand des Bildes abgeschnitten wird, oder legt sie fest. Lese/Schreib Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Gibt die prozentuale Anzahl der realen Bildbreite zurück, die am rechten Rand des Bildes abgeschnitten wird, oder legt sie fest. Lese/Schreib Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Gibt die prozentuale Anzahl der realen Bildhöhe zurück, die am oberen Rand des Bildes abgeschnitten wird, oder legt sie fest. Lese/Schreib Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Gibt die DPI zurück, die zum Füllen eines Bildes verwendet wird, oder legt sie fest. Lese/Schreib Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Gibt das Bild zurück. Nur-Lesen [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Gibt den Bildfüllmodus zurück oder legt ihn fest. Lese/Schreib [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Gibt die untere Kante des Füllrechtecks zurück oder legt sie fest, definiert durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Ausgleich. Lese/Schreib Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Gibt die linke Kante des Füllrechtecks zurück oder legt sie fest, definiert durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Ausgleich. Lese/Schreib Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Gibt die rechte Kante des Füllrechtecks zurück oder legt sie fest, definiert durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Ausgleich. Lese/Schreib Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Gibt die obere Kante des Füllrechtecks zurück oder legt sie fest, definiert durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Ausgleich. Lese/Schreib Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Gibt zurück, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung steuert den Startpunkt des Texturmusters und dessen Wiederholung über die Form. Lese/Schreib [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Spiegelt die Texturfliese horizontal, vertikal oder um beide Achsen. Lese/Schreib [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkt zurück oder legt ihn fest. Ein positiver Wert verschiebt die Textur nach rechts, ein negativer nach links. Lese/Schreib Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkt zurück oder legt ihn fest. Ein positiver Wert verschiebt die Textur nach unten, ein negativer nach oben. Lese/Schreib Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Gibt die horizontale Skalierung für die Texturfüllung als Prozentsatz zurück oder legt sie fest. Lese/Schreib Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Gibt die vertikale Skalierung für die Texturfüllung als Prozentsatz zurück oder legt sie fest. Lese/Schreib Single. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Komprimiert das Bild, indem es seine Größe basierend auf der Formengröße und der angegebenen Auflösung reduziert. Optional löscht es auch abgeschnittene Bereiche. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimiert das Bild, indem es seine Größe basierend auf der Formengröße und der angegebenen Auflösung reduziert. Optional löscht es auch abgeschnittene Bereiche. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Löscht abgeschnittene Bereiche des Füllbildes. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IPictureFillFormat](../ipicturefillformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->