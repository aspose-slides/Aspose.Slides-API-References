---
title: PictureFillFormat
second_title: Aspose.Sildes for .NET API Referencia
description: Kép kitöltési stílust képvisel.
type: docs
weight: 9370
url: /hu/aspose.slides/picturefillformat/
---
## PictureFillFormat osztály

Kép kitöltési stílust képvisel.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely le van vágva a kép aljáról. Olvasható/írható Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely le van vágva a kép bal oldaláról. Olvasható/írható Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely le van vágva a kép jobb oldaláról. Olvasható/írható Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely le van vágva a kép tetejéről. Olvasható/írható Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Visszaadja vagy beállítja a kép kitöltéséhez használt dpi értéket. Olvasható/írható Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Visszaadja a képet. Csak olvasható [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Visszaadja vagy beállítja a kép kitöltési módját. Olvasható/írható [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Visszaadja vagy beállítja a kitöltés téglalap alsó szélét, amelyet a forma körülvett mező alsó szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső eltolást, a negatív százalék külső eltolást jelent. Olvasható/írható Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Visszaadja vagy beállítja a kitöltés téglalap bal szélét, amelyet a forma körülvett mező bal szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső eltolást, a negatív százalék külső eltolást jelent. Olvasható/írható Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Visszaadja vagy beállítja a kitöltés téglalap jobb szélét, amelyet a forma körülvett mező jobb szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső eltolást, a negatív százalék külső eltolást jelent. Olvasható/írható Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Visszaadja vagy beállítja a kitöltés téglalap felső szélét, amelyet a forma körülvett mező felső szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső eltolást, a negatív százalék külső eltolást jelent. Olvasható/írható Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Visszaadja vagy beállítja a textúra alakzaton belüli igazítását. Ez a beállítás szabályozza a textúraminta kiindulópontját és azt, hogyan ismétlődik az alakzaton. Olvasható/írható [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Megfordítja a textúra csempe vízszintes, függőleges vagy mindkét tengelye mentén. Olvasható/írható [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma kiindulópontjától pontokban. A pozitív érték jobbra, a negatív balra mozgatja a textúrát. Olvasható/írható Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Visszaadja vagy beállítja a textúra függőleges eltolását a forma kiindulópontjától pontokban. A pozitív érték lefelé, a negatív felfelé mozgatja a textúrát. Olvasható/írható Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Visszaadja vagy beállítja a textúra kitöltés vízszintes méretezését százalékban. Olvasható/írható Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Visszaadja vagy beállítja a textúra kitöltés függőleges méretezését százalékban. Olvasható/írható Single. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan a levágott területeket is eltávolítja. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan a levágott területeket is eltávolítja. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Törli a kitöltő kép levágott területeit. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IPictureFillFormat](../ipicturefillformat)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->