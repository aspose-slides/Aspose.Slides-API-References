---
title: IPictureFillFormat
second_title: Aspose.Sildes .NET API referenciája
description: Képkitöltési stílust képvisel.
type: docs
weight: 6650
url: /hu/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat interfész

Képkitöltési stílust képvisel.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Lehetővé teszi az alap IFillParamSource interfész lekérését. Csak olvasható [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely a kép aljáról le van vágva. Olvasás/írás Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép bal oldaláról le van vágva. Olvasás/írás Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép jobb oldaláról le van vágva. Olvasás/írás Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely a kép tetejéről le van vágva. Olvasás/írás Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Visszaadja vagy beállítja a kép kitöltéséhez használt dpi értéket. Olvasás/írás Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Visszaadja a képet. Csak olvasható [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Visszaadja vagy beállítja a kép kitöltési módot. Olvasás/írás [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Visszaadja vagy beállítja a kitöltő téglalap alsó élét, amelyet egy százalékos eltolás határoz meg a forma keretének alsó élétől. A pozitív százalék egy belső eltolást jelent, míg a negatív százalék egy külső eltolást. Olvasás/írás Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Visszaadja vagy beállítja a kitöltő téglalap bal élét, amelyet egy százalékos eltolás határoz meg a forma keretének bal élétől. A pozitív százalék egy belső eltolást jelent, míg a negatív százalék egy külső eltolást. Olvasás/írás Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Visszaadja vagy beállítja a kitöltő téglalap jobb élét, amelyet egy százalékos eltolás határoz meg a forma keretének jobb élétől. A pozitív százalék egy belső eltolást jelent, míg a negatív százalék egy külső eltolást. Olvasás/írás Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Visszaadja vagy beállítja a kitöltő téglalap felső élét, amelyet egy százalékos eltolás határoz meg a forma keretének felső élétől. A pozitív százalék egy belső eltolást jelent, míg a negatív százalék egy külső eltolást. Olvasás/írás Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Visszaadja vagy beállítja, hogy a textúra hogyan van igazítva a forma belsejében. Ez a beállítás szabályozza a textúraminta kiindulópontját és azt, hogy hogyan ismétlődik a formában. Olvasás/írás [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Megfordítja a textúra csempét a horizontális, vertikális vagy mindkét tengelye körül. Olvasás/írás [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma kiindulópontjától pontokban. A pozitív érték jobbra mozgatja a textúrát, a negatív balra. Olvasás/írás Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Visszaadja vagy beállítja a textúra függőleges eltolását a forma kiindulópontjától pontokban. A pozitív érték lejjebb mozgatja a textúrát, a negatív felfelé. Olvasás/írás Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Visszaadja vagy beállítja a textúra kitöltés vízszintes méretezését százalékban. Olvasás/írás Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Visszaadja vagy beállítja a textúra kitöltés függőleges méretezését százalékban. Olvasás/írás Single. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan a levágott területeket is törli. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan a levágott területeket is törli. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | A kitöltő kép levágott területeinek törlése. |

### Lásd még

* interfész [IFillParamSource](../ifillparamsource)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->