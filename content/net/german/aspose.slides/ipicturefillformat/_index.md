---
title: IPictureFillFormat
second_title: Aspose.Slides für .NET API Referenz
description: Stellt einen Bildfüllstil dar.
type: docs
weight: 6450
url: /de/aspose.slides/ipicturefillformat/
---

## IPictureFillFormat-Schnittstelle

Stellt einen Bildfüllstil dar.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Ermöglicht den Zugriff auf die Basis-Schnittstelle IFillParamSource. Nur lesen [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Gibt die Anzahl der Prozent der tatsächlichen Bildhöhe zurück oder setzt sie, die vom unteren Rand des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Gibt die Anzahl der Prozent der tatsächlichen Bildbreite zurück oder setzt sie, die vom linken Rand des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Gibt die Anzahl der Prozent der tatsächlichen Bildbreite zurück oder setzt sie, die vom rechten Rand des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Gibt die Anzahl der Prozent der tatsächlichen Bildhöhe zurück oder setzt sie, die vom oberen Rand des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Gibt die DPI zurück oder setzt sie, die verwendet wird, um ein Bild zu füllen. Lese-/Schreibzugriff Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Gibt das Bild zurück. Nur lesen [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Gibt den Bildfüllmodus zurück oder setzt ihn. Lese-/Schreibzugriff [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Gibt den unteren Rand des Füllrechtecks zurück oder setzt ihn, der durch einen prozentualen Versatz vom unteren Rand des Begrenzungsrahmen des Objekts definiert ist. Ein positiver Prozentsatz gibt ein Einrücken an, während ein negativer Prozentsatz ein Herausstehen angibt. Lese-/Schreibzugriff Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Gibt den linken Rand des Füllrechtecks zurück oder setzt ihn, der durch einen prozentualen Versatz vom linken Rand des Begrenzungsrahmen des Objekts definiert ist. Ein positiver Prozentsatz gibt ein Einrücken an, während ein negativer Prozentsatz ein Herausstehen angibt. Lese-/Schreibzugriff Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Gibt den rechten Rand des Füllrechtecks zurück oder setzt ihn, der durch einen prozentualen Versatz vom rechten Rand des Begrenzungsrahmen des Objekts definiert ist. Ein positiver Prozentsatz gibt ein Einrücken an, während ein negativer Prozentsatz ein Herausstehen angibt. Lese-/Schreibzugriff Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Gibt den oberen Rand des Füllrechtecks zurück oder setzt ihn, der durch einen prozentualen Versatz vom oberen Rand des Begrenzungsrahmen des Objekts definiert ist. Ein positiver Prozentsatz gibt ein Einrücken an, während ein negativer Prozentsatz ein Herausstehen angibt. Lese-/Schreibzugriff Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Gibt zurück oder setzt, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung steuert den Ausgangspunkt des Texturmusters und wie es sich über die Form wiederholt. Lese-/Schreibzugriff [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Dreht die Texturfliese um ihre horizontale, vertikale oder beide Achsen. Lese-/Schreibzugriff [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder setzt ihn. Ein positiver Wert verschiebt die Textur nach rechts, während ein negativer Wert sie nach links verschiebt. Lese-/Schreibzugriff Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder setzt ihn. Ein positiver Wert verschiebt die Textur nach unten, während ein negativer Wert sie nach oben verschiebt. Lese-/Schreibzugriff Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Gibt die horizontale Skalierung für die Texturfüllung als Prozentsatz zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Gibt die vertikale Skalierung für die Texturfüllung als Prozentsatz zurück oder setzt sie. Lese-/Schreibzugriff Single. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden auch die abgeschnittenen Bereiche gelöscht. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden auch die abgeschnittenen Bereiche gelöscht. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Löscht die abgeschnittenen Bereiche des Füllbildes. |

### Siehe auch

* Schnittstelle [IFillParamSource](../ifillparamsource)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->