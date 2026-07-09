---
title: IPictureFillFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt einen Bildfüllstil dar.
type: docs
weight: 6650
url: /de/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat Schnittstelle

Stellt einen Bildfüllstil dar.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Ermöglicht das Abrufen der Basis-IFillParamSource Schnittstelle. Nur lesbar [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Gibt die Anzahl der Prozentsätze der realen Bildhöhe zurück, die am unteren Rand des Bildes abgeschnitten werden, oder legt sie fest. Lesen/Schreiben Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Gibt die Anzahl der Prozentsätze der realen Bildbreite zurück, die am linken Rand des Bildes abgeschnitten werden, oder legt sie fest. Lesen/Schreiben Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Gibt die Anzahl der Prozentsätze der realen Bildbreite zurück, die am rechten Rand des Bildes abgeschnitten werden, oder legt sie fest. Lesen/Schreiben Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Gibt die Anzahl der Prozentsätze der realen Bildhöhe zurück, die am oberen Rand des Bildes abgeschnitten werden, oder legt sie fest. Lesen/Schreiben Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Gibt die DPI zurück, die zum Füllen eines Bildes verwendet wird, oder legt sie fest. Lesen/Schreiben Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Gibt das Bild zurück. Nur lesbar [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Gibt den Bildfüllmodus zurück oder legt ihn fest. Lesen/Schreiben [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Gibt die untere Kante des Füllrechtecks zurück, die durch einen prozentualen Versatz vom unteren Rand der Begrenzungsbox der Form definiert ist, oder legt sie fest. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Auslauf. Lesen/Schreiben Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Gibt die linke Kante des Füllrechtecks zurück, die durch einen prozentualen Versatz vom linken Rand der Begrenzungsbox der Form definiert ist, oder legt sie fest. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Auslauf. Lesen/Schreiben Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Gibt die rechte Kante des Füllrechtecks zurück, die durch einen prozentualen Versatz vom rechten Rand der Begrenzungsbox der Form definiert ist, oder legt sie fest. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Auslauf. Lesen/Schreiben Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Gibt die obere Kante des Füllrechtecks zurück, die durch einen prozentualen Versatz vom oberen Rand der Begrenzungsbox der Form definiert ist, oder legt sie fest. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Auslauf. Lesen/Schreiben Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Gibt zurück, wie die Textur innerhalb der Form ausgerichtet ist, oder legt dies fest. Diese Einstellung steuert den Ausgangspunkt des Texturmusters und wie es über die Form wiederholt wird. Lesen/Schreiben [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Spiegelt das Textur-Kachel um seine horizontale, vertikale oder beide Achsen. Lesen/Schreiben [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder legt ihn fest. Ein positiver Wert verschiebt die Textur nach rechts, ein negativer Wert nach links. Lesen/Schreiben Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder legt ihn fest. Ein positiver Wert verschiebt die Textur nach unten, ein negativer Wert nach oben. Lesen/Schreiben Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Gibt die horizontale Skalierung für die Texturfüllung als Prozentsatz zurück oder legt sie fest. Lesen/Schreiben Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Gibt die vertikale Skalierung für die Texturfüllung als Prozentsatz zurück oder legt sie fest. Lesen/Schreiben Single. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden auch beschnittene Bereiche gelöscht. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden auch beschnittene Bereiche gelöscht. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Löscht beschnittene Bereiche des Füllbildes. |

### Siehe auch

* Schnittstelle [IFillParamSource](../ifillparamsource)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->