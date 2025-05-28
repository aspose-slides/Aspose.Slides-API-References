---
title: IPictureFillFormat
second_title: Aspose.Slides für .NET API-Referenz
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
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Ermöglicht den Zugriff auf die Basis-IFillParamSource-Schnittstelle. Nur lesbar [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Gibt die Anzahl der Prozentsätze der tatsächlichen Bildhöhe zurück oder legt sie fest, die von der Unterseite des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Gibt die Anzahl der Prozentsätze der tatsächlichen Bildbreite zurück oder legt sie fest, die von der linken Seite des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Gibt die Anzahl der Prozentsätze der tatsächlichen Bildbreite zurück oder legt sie fest, die von der rechten Seite des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Gibt die Anzahl der Prozentsätze der tatsächlichen Bildhöhe zurück oder legt sie fest, die von der Oberseite des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Gibt die DPI zurück oder legt sie fest, die zum Füllen eines Bildes verwendet wird. Lese-/Schreibzugriff Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Gibt das Bild zurück. Nur lesbar [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Gibt den Bildfüllmodus zurück oder legt ihn fest. Lese-/Schreibzugriff [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Gibt die untere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Offset von der unteren Kante des Begrenzungsrahmens der Form definiert ist. Ein positiver Prozentsatz gibt einen Innenabstand an, während ein negativer Prozentsatz einen Außenabstand angibt. Lese-/Schreibzugriff Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Gibt die linke Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Offset von der linken Kante des Begrenzungsrahmens der Form definiert ist. Ein positiver Prozentsatz gibt einen Innenabstand an, während ein negativer Prozentsatz einen Außenabstand angibt. Lese-/Schreibzugriff Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Gibt die rechte Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Offset von der rechten Kante des Begrenzungsrahmens der Form definiert ist. Ein positiver Prozentsatz gibt einen Innenabstand an, während ein negativer Prozentsatz einen Außenabstand angibt. Lese-/Schreibzugriff Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Gibt die obere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Offset von der oberen Kante des Begrenzungsrahmens der Form definiert ist. Ein positiver Prozentsatz gibt einen Innenabstand an, während ein negativer Prozentsatz einen Außenabstand angibt. Lese-/Schreibzugriff Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Gibt zurück oder legt fest, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung steuert den Startpunkt des Texturmusters und wie es sich über die Form wiederholt. Lese-/Schreibzugriff [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Spiegel das Textur-Kachel um seine horizontale, vertikale oder beide Achsen. Lese-/Schreibzugriff [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Gibt den horizontalen Offset der Textur von der Ursprung der Form in Punkten zurück oder legt ihn fest. Ein positiver Wert bewegt die Textur nach rechts, während ein negativer Wert sie nach links bewegt. Lese-/Schreibzugriff Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Gibt den vertikalen Offset der Textur von der Ursprung der Form in Punkten zurück oder legt ihn fest. Ein positiver Wert bewegt die Textur nach unten, während ein negativer Wert sie nach oben bewegt. Lese-/Schreibzugriff Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Gibt den horizontalen Maßstab für die Texturfüllung als Prozentsatz zurück oder legt ihn fest. Lese-/Schreibzugriff Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Gibt den vertikalen Maßstab für die Texturfüllung als Prozentsatz zurück oder legt ihn fest. Lese-/Schreibzugriff Single. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Komprimiert das Bild, indem die Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden auch die abgeschnittenen Bereiche gelöscht. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimiert das Bild, indem die Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden auch die abgeschnittenen Bereiche gelöscht. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Löscht die abgeschnittenen Bereiche des Bildfüllers. |

### Siehe auch

* Schnittstelle [IFillParamSource](../ifillparamsource)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->