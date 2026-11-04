---
title: PictureFillFormat
second_title: Aspose.Sildes .NET API referencia
description: Képkitöltési stílust képvisel.
type: docs
weight: 9410
url: /hu/aspose.slides/picturefillformat/
---
## PictureFillFormat osztály

A képkitöltési stílust képviseli.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész elérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép aljáról levágásra kerül. Olvasható/írható Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép bal oldaláról levágásra kerül. Olvasható/írható Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép jobb oldaláról levágásra kerül. Olvasható/írható Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép tetejéről levágásra kerül. Olvasható/írható Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Visszaadja vagy beállítja a DPI értéket, amely a kép kitöltéséhez használatos. Olvasható/írható Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Visszaadja a picture-t. Csak olvasható [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Visszaadja vagy beállítja a kép kitöltési módot. Olvasható/írható [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap alsó szélét, amely a forma határolókeretének alsó szélétől számított százalékos eltolással van meghatározva. A pozitív százalék egy belülre tolást jelent, míg a negatív egy kifelé tolást. Olvasható/írható Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap bal szélét, amely a forma határolókeretének bal szélétől számított százalékos eltolással van meghatározva. A pozitív százalék egy belülre tolást jelent, míg a negatív egy kifelé tolást. Olvasható/írható Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap jobb szélét, amely a forma határolókeretének jobb szélétől számított százalékos eltolással van meghatározva. A pozitív százalék egy belülre tolást jelent, míg a negatív egy kifelé tolást. Olvasható/írható Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Visszaadja vagy beállítja a kitöltési téglalap felső szélét, amely a forma határolókeretének felső szélétől számított százalékos eltolással van meghatározva. A pozitív százalék egy belülre tolást jelent, míg a negatív egy kifelé tolást. Olvasható/írható Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Visszaadja vagy beállítja, hogyan van igazítva a textúra a alakzatban. Ez a beállítás határozza meg a textúramintázat kiindulópontját és azt, hogy hogyan ismétlődik az alakzatban. Olvasható/írható [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Tükrözi a textúra csempét vízszintes, függőleges vagy mindkét tengely körül. Olvasható/írható [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma kiindulási pontjától pontban. A pozitív érték jobbra mozgatja a textúrát, a negatív balra. Olvasható/írható Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Visszaadja vagy beállítja a textúra függőleges eltolását a forma kiindulási pontjától pontban. A pozitív érték lefelé mozgatja a textúrát, a negatív felfelé. Olvasható/írható Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Visszaadja vagy beállítja a textúra kitöltés vízszintes méretezését százalékban. Olvasható/írható Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Visszaadja vagy beállítja a textúra kitöltés függőleges méretezését százalékban. Olvasható/írható Single. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan a levágott területeket is törli. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan a levágott területeket is törli. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | A kitöltő Picture levágott területeinek törlése. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IPictureFillFormat](../ipicturefillformat)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->