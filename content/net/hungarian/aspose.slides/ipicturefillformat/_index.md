---
title: IPictureFillFormat
second_title: Aspose.Sildes .NET API hivatkozás
description: Kép kitöltési stílust képvisel.
type: docs
weight: 6630
url: /hu/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat interfész

Represents a picture fill style.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Tulajdonságok

| Name | Description |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Lehetővé teszi az alap IFillParamSource interfész lekérését. Csak olvasható [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép aljáról levágásra kerül. Olvasás/írás Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép bal oldaláról levágásra kerül. Olvasás/írás Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép jobb oldaláról levágásra kerül. Olvasás/írás Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Visszaadja vagy beállítja a valós kémmagasság százalékos arányát, amely a kép tetejéről levágásra kerül. Olvasás/írás Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Visszaadja vagy beállítja a kép kitöltéséhez használt dpi értéket. Olvasás/írás Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Visszaadja a képet. Csak olvasható [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Visszaadja vagy beállítja a képletöltés módját. Olvasás/írás [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap alsó élét, amely a forma határoló keretének alsó élétől százalékos eltolással van meghatározva. A pozitív százalék belső margót jelent, míg a negatív százalék külső margót. Olvasás/írás Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap bal élét, amely a forma határoló keretének bal oldalától százalékos eltolással van meghatározva. A pozitív százalék belső margót jelent, míg a negatív százalék külső margót. Olvasás/írás Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap jobb élét, amely a forma határoló keretének jobb oldalától százalékos eltolással van meghatározva. A pozitív százalék belső margót jelent, míg a negatív százalék külső margót. Olvasás/írás Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap felső élét, amely a forma határoló keretének felső élétől százalékos eltolással van meghatározva. A pozitív százalék belső margót jelent, míg a negatív százalék külső margót. Olvasás/írás Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Visszaadja vagy beállítja, hogyan igazodik a textúra a formán belül. Ez a beállítás szabályozza a textúramintázat kiindulópontját és a forma feletti ismétlődés módját. Olvasás/írás [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Megfordítja a textúratéglát vízszintes, függőleges vagy mindkét tengelye körül. Olvasás/írás [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma kiindulópontjától pontokban. A pozitív érték jobbra mozgatja a textúrát, a negatív balra. Olvasás/írás Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Visszaadja vagy beállítja a textúra függőleges eltolását a forma kiindulópontjától pontokban. A pozitív érték lefelé mozgatja a textúrát, a negatív felfelé. Olvasás/írás Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Visszaadja vagy beállítja a textúra kitöltés vízszintes méretezését százalékban. Olvasás/írás Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Visszaadja vagy beállítja a textúra kitöltés függőleges méretezését százalékban. Olvasás/írás Single. |

## Módszerek

| Name | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | A képet a forma mérete és a megadott felbontás alapján kicsinyíti, csökkentve méretét. Opcionálisan a levágott területeket is törli. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | A képet a forma mérete és a megadott felbontás alapján kicsinyíti, csökkentve méretét. Opcionálisan a levágott területeket is törli. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Törli a kitöltő kép levágott területeit. |

### Lásd még

* interfész [IFillParamSource](../ifillparamsource)
* névtér [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->