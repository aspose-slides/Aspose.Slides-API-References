---
title: IPictureFillFormat
second_title: Aspose.Sildes a .NET API hivatkozás
description: Képkitöltési stílust képvisel.
type: docs
weight: 6670
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
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Lehetővé teszi a base IFillParamSource interfész elérését. Csak olvasható [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép alja felől levágásra kerül. Olvasás/írás Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép bal oldaláról levágásra kerül. Olvasás/írás Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról levágásra kerül. Olvasás/írás Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép tetejéről levágásra kerül. Olvasás/írás Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Visszaadja vagy beállítja a képet kitöltésére használt DPI értéket. Olvasás/írás Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Visszaadja a képet. Csak olvasható [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Visszaadja vagy beállítja a kép kitöltési módot. Olvasás/írás [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap alsó élét, amely a forma keretének alsó szélétől származó százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék külső eltolást jelent. Olvasás/írás Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap bal szélét, amely a forma keretének bal szélétől származó százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék külső eltolást jelent. Olvasás/írás Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap jobb szélét, amely a forma keretének jobb szélétől származó százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék külső eltolást jelent. Olvasás/írás Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap felső szélét, amely a forma keretének felső szélétől származó százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék külső eltolást jelent. Olvasás/írás Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Visszaadja vagy beállítja, hogy a textúra hogyan legyen igazítva a forma belsejében. Ez a beállítás szabályozza a textúraminta kiindulópontját és annak ismétlődését a formán. Olvasás/írás [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Megfordítja a textúra csempét a vízszintes, függőleges vagy mindkét tengely körül. Olvasás/írás [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma eredetétől pontban. A pozitív érték jobbra, a negatív balra mozgatja a textúrát. Olvasás/írás Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Visszaadja vagy beállítja a textúra függőleges eltolását a forma eredetétől pontban. A pozitív érték lefelé, a negatív felfelé mozgatja a textúrát. Olvasás/írás Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Visszaadja vagy beállítja a textúra kitöltésének vízszintes méretezését százalékban. Olvasás/írás Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Visszaadja vagy beállítja a textúra kitöltésének függőleges méretezését százalékban. Olvasás/írás Single. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan törli a levágott területeket is. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan törli a levágott területeket is. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Törli a kitöltési Picture levágott területeit. |

### Lásd még

* interfész [IFillParamSource](../ifillparamsource)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->