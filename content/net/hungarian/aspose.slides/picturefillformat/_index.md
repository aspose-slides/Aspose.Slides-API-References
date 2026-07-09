---
title: PictureFillFormat
second_title: Aspose.Sildes a .NET API referencia
description: Képkitöltési stílust képvisel.
type: docs
weight: 9390
url: /hu/aspose.slides/picturefillformat/
---
## PictureFillFormat osztály

Képkitöltési stílust képvisel.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész elérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Visszaadja vagy beállítja a valós képmagasság levágott százalékos arányát a kép alján. Olvasás/írás Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Visszaadja vagy beállítja a valós képszélesség levágott százalékos arányát a kép bal oldalán. Olvasás/írás Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Visszaadja vagy beállítja a valós képszélesség levágott százalékos arányát a kép jobb oldalán. Olvasás/írás Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Visszaadja vagy beállítja a valós képmagasság levágott százalékos arányát a kép tetején. Olvasás/írás Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Visszaadja vagy beállítja a képet kitöltéshez használt dpi értéket. Olvasás/írás Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Visszaadja a képet. Csak olvasható [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Visszaadja vagy beállítja a kép kitöltési módot. Olvasás/írás [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Visszaadja vagy beállítja a kitöltő téglalap alsó szélét, amely a forma határoló dobozának alsó szélétől számított százalékos eltolással van meghatározva. A pozitív százalék belső kitöltést jelent, a negatív pedig külső kitöltést. Olvasás/írás Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Visszaadja vagy beállítja a kitöltő téglalap bal szélét, amely a forma határoló dobozának bal szélétől számított százalékos eltolással van meghatározva. A pozitív százalék belső kitöltést jelent, a negatív pedig külső kitöltést. Olvasás/írás Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Visszaadja vagy beállítja a kitöltő téglalap jobb szélét, amely a forma határoló dobozának jobb szélétől számított százalékos eltolással van meghatározva. A pozitív százalék belső kitöltést jelent, a negatív pedig külső kitöltést. Olvasás/írás Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Visszaadja vagy beállítja a kitöltő téglalap felső szélét, amely a forma határoló dobozának felső szélétől számított százalékos eltolással van meghatározva. A pozitív százalék belső kitöltést jelent, a negatív pedig külső kitöltést. Olvasás/írás Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Visszaadja vagy beállítja, hogyan igazodik a textúra a formán belül. Ez a beállítás határozza meg a textúraminta kiindulópontját és annak ismétlődését a formán. Olvasás/írás [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Megfordítja a textúra csempét a vízszintes, függőleges vagy mindkét tengely körül. Olvasás/írás [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma eredeti pontjából pontban. A pozitív érték jobbra, a negatív balra mozdítja a textúrát. Olvasás/írás Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Visszaadja vagy beállítja a textúra függőleges eltolását a forma eredeti pontjából pontban. A pozitív érték lefelé, a negatív felfelé mozdítja a textúrát. Olvasás/írás Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Visszaadja vagy beállítja a textúra vízszintes méretarányát százalékban. Olvasás/írás Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Visszaadja vagy beállítja a textúra függőleges méretarányát százalékban. Olvasás/írás Single. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Tömöríti a képet a mérete csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan törli a levágott területeket. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Tömöríti a képet a mérete csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan törli a levágott területeket. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Törli a kitöltő kép levágott területeit. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IPictureFillFormat](../ipicturefillformat)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->