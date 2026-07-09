---
title: PictureFillFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje styl vyplnění obrázkem.
type: docs
weight: 9390
url: /cs/aspose.slides/picturefillformat/
---
## PictureFillFormat třída

Reprezentuje styl vyplnění obrázkem.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty ze spodní části obrázku. Číst/Zapisovat Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z levé strany obrázku. Číst/Zapisovat Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z pravé strany obrázku. Číst/Zapisovat Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty z horní části obrázku. Číst/Zapisovat Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Vrací nebo nastavuje DPI, které se používá k vyplnění obrázku. Číst/Zapisovat Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Vrací obrázek. Pouze pro čtení [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Vrací nebo nastavuje režim vyplnění obrázkem. Číst/Zapisovat [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Vrací nebo nastavuje spodní okraj výplňového obdélníku definovaný procentuálním posunem od spodního okraje ohraničovacího rámce tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Číst/Zapisovat Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Vrací nebo nastavuje levý okraj výplňového obdélníku definovaný procentuálním posunem od levého okraje ohraničovacího rámce tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Číst/Zapisovat Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Vrací nebo nastavuje pravý okraj výplňového obdélníku definovaný procentuálním posunem od pravého okraje ohraničovacího rámce tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Číst/Zapisovat Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Vrací nebo nastavuje horní okraj výplňového obdélníku definovaný procentuálním posunem od horního okraje ohraničovacího rámce tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Číst/Zapisovat Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Vrací nebo nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení určuje výchozí bod vzoru textury a způsob, jakým se opakuje po celém tvaru. Číst/Zapisovat [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Otočí dlaždici textury kolem její vodorovné, svislé nebo obou osí. Číst/Zapisovat [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Vrací nebo nastavuje vodorovný posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, záporná hodnota doleva. Číst/Zapisovat Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Vrací nebo nastavuje svislý posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, záporná hodnota nahoru. Číst/Zapisovat Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Vrací nebo nastavuje vodorovné měřítko pro výplň texturou jako procento. Číst/Zapisovat Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Vrací nebo nastavuje svislé měřítko pro výplň texturou jako procento. Číst/Zapisovat Single. |

## Metody

| Název | Popis |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Odstraní oříznuté oblasti vyplňovacího obrázku. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovná s uvedeným objektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Viz také

* třída [PVIObject](../pviobject)
* rozhraní [IPictureFillFormat](../ipicturefillformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->