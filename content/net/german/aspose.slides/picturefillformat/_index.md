---
title: PictureFillFormat
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt einen Bildfüllstil dar.
type: docs
weight: 9390
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
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPresentationComponent-Schnittstelle. Nur lesbar [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Gibt die Anzahl der Prozentsätze der realen Bildhöhe zurück, die am unteren Rand des Bildes abgeschnitten werden, oder legt sie fest. Lesen/Schreiben Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Gibt die Anzahl der Prozentsätze der realen Bildbreite zurück, die am linken Rand des Bildes abgeschnitten werden, oder legt sie fest. Lesen/Schreiben Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Gibt die Anzahl der Prozentsätze der realen Bildbreite zurück, die am rechten Rand des Bildes abgeschnitten werden, oder legt sie fest. Lesen/Schreiben Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Gibt die Anzahl der Prozentsätze der realen Bildhöhe zurück, die am oberen Rand des Bildes abgeschnitten werden, oder legt sie fest. Lesen/Schreiben Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Gibt die DPI zurück, die zum Füllen eines Bildes verwendet werden, oder legt sie fest. Lesen/Schreiben Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Gibt das Bild zurück. Nur lesbar [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Gibt den Bildfüllmodus zurück oder legt ihn fest. Lesen/Schreiben [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Gibt die untere Kante des Füllrechtecks zurück, die durch einen prozentualen Versatz von der unteren Kante des Begrenzungsrahmens der Form definiert ist, oder legt sie fest. Lesen/Schreiben Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Gibt die linke Kante des Füllrechtecks zurück, die durch einen prozentualen Versatz von der linken Kante des Begrenzungsrahmens der Form definiert ist, oder legt sie fest. Lesen/Schreiben Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Gibt die rechte Kante des Füllrechtecks zurück, die durch einen prozentualen Versatz von der rechten Kante des Begrenzungsrahmens der Form definiert ist, oder legt sie fest. Lesen/Schreiben Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Gibt die obere Kante des Füllrechtecks zurück, die durch einen prozentualen Versatz von der oberen Kante des Begrenzungsrahmens der Form definiert ist, oder legt sie fest. Lesen/Schreiben Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Gibt zurück, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung steuert den Ausgangspunkt des Texturmusters und dessen Wiederholung über die Form hinweg. Lesen/Schreiben [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Spiegelt die Texturfliese um ihre horizontale, vertikale oder beide Achsen. Lesen/Schreiben [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder legt ihn fest. Ein positiver Wert verschiebt die Textur nach rechts, ein negativer nach links. Lesen/Schreiben Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder legt ihn fest. Ein positiver Wert verschiebt die Textur nach unten, ein negativer nach oben. Lesen/Schreiben Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Gibt die horizontale Skalierung für die Texturfüllung als Prozentsatz zurück oder legt sie fest. Lesen/Schreiben Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Gibt die vertikale Skalierung für die Texturfüllung als Prozentsatz zurück oder legt sie fest. Lesen/Schreiben Single. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung verringert. Optional löscht es auch beschnittene Bereiche. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung verringert. Optional löscht es auch beschnittene Bereiche. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Löscht beschnittene Bereiche des Füllbildes. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IPictureFillFormat](../ipicturefillformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->