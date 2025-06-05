---
title: PictureFillFormat
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt einen Bildfüllstil dar.
type: docs
weight: 9120
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
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Erlaubt den Zugriff auf die basierende IPresentationComponent-Schnittstelle. Nur lesbar [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Gibt die Anzahl der Prozentsätze der tatsächlichen Bildhöhe zurück oder setzt diese, die vom unteren Rand des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Gibt die Anzahl der Prozentsätze der tatsächlichen Bildbreite zurück oder setzt diese, die vom linken Rand des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Gibt die Anzahl der Prozentsätze der tatsächlichen Bildbreite zurück oder setzt diese, die vom rechten Rand des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Gibt die Anzahl der Prozentsätze der tatsächlichen Bildhöhe zurück oder setzt diese, die vom oberen Rand des Bildes abgeschnitten werden. Lese-/Schreibzugriff Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Gibt die DPI zurück oder setzt diese, die verwendet wird, um ein Bild zu füllen. Lese-/Schreibzugriff Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Gibt das Bild zurück. Nur lesbar [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Gibt den Bildfüllmodus zurück oder setzt diesen. Lese-/Schreibzugriff [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Gibt die untere Kante des Füllrechtecks zurück oder setzt diese, die durch einen prozentualen Offset vom unteren Rand des Begrenzungsrahmens der Form definiert ist. Ein positiver Prozentsatz spezifiziert einen Innenabstand, während ein negativer Prozentsatz einen Außenabstand angibt. Lese-/Schreibzugriff Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Gibt die linke Kante des Füllrechtecks zurück oder setzt diese, die durch einen prozentualen Offset vom linken Rand des Begrenzungsrahmens der Form definiert ist. Ein positiver Prozentsatz spezifiziert einen Innenabstand, während ein negativer Prozentsatz einen Außenabstand angibt. Lese-/Schreibzugriff Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Gibt die rechte Kante des Füllrechtecks zurück oder setzt diese, die durch einen prozentualen Offset vom rechten Rand des Begrenzungsrahmens der Form definiert ist. Ein positiver Prozentsatz spezifiziert einen Innenabstand, während ein negativer Prozentsatz einen Außenabstand angibt. Lese-/Schreibzugriff Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Gibt die obere Kante des Füllrechtecks zurück oder setzt diese, die durch einen prozentualen Offset vom oberen Rand des Begrenzungsrahmens der Form definiert ist. Ein positiver Prozentsatz spezifiziert einen Innenabstand, während ein negativer Prozentsatz einen Außenabstand angibt. Lese-/Schreibzugriff Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Gibt zurück oder setzt, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung steuert den Ausgangspunkt des Texturmusters und wie es sich über die Form wiederholt. Lese-/Schreibzugriff [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Flippt die Texturplatte um ihre horizontale, vertikale oder beide Achsen. Lese-/Schreibzugriff [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Gibt den horizontalen Offset der Textur vom Ursprung der Form in Punkten zurück oder setzt diesen. Ein positiver Wert bewegt die Textur nach rechts, während ein negativer Wert sie nach links bewegt. Lese-/Schreibzugriff Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Gibt den vertikalen Offset der Textur vom Ursprung der Form in Punkten zurück oder setzt diesen. Ein positiver Wert bewegt die Textur nach unten, während ein negativer Wert sie nach oben bewegt. Lese-/Schreibzugriff Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Gibt die horizontale Skalierung für die Texturfüllung als Prozentsatz zurück oder setzt diese. Lese-/Schreibzugriff Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Gibt die vertikale Skalierung für die Texturfüllung als Prozentsatz zurück oder setzt diese. Lese-/Schreibzugriff Single. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Komprimiert das Bild, indem die Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden auch beschnittene Bereiche gelöscht. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimiert das Bild, indem die Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden auch beschnittene Bereiche gelöscht. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Löscht die beschnittenen Bereiche des Füllbildes. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Siehe Auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IPictureFillFormat](../ipicturefillformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->