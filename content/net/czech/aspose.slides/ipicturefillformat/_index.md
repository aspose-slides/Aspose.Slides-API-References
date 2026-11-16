---
title: IPictureFillFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje styl výplně obrázkem.
type: docs
weight: 6670
url: /cs/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat rozhraní

Representuje styl výplně obrázkem.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Umožňuje získat základní rozhraní IFillParamSource. Pouze pro čtení [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty ze spodní části obrázku. Čtení/zápis Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z levé strany obrázku. Čtení/zápis Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z pravé strany obrázku. Čtení/zápis Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty z horní části obrázku. Čtení/zápis Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Vrací nebo nastavuje DPI, které se používá k vyplnění obrázku. Čtení/zápis Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Vrací obrázek. Pouze pro čtení [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Vrací nebo nastavuje režim vyplnění obrázkem. Čtení/zápis [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Vrací nebo nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním posunem od spodního okraje ohraničujícího rámečku tvaru. Kladné procento určuje vnitřní odsazení, záporné procento určuje vnější odsazení. Čtení/zápis Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Vrací nebo nastavuje levý okraj výplňového obdélníku, který je definován procentuálním posunem od levého okraje ohraničujícího rámečku tvaru. Kladné procento určuje vnitřní odsazení, záporné procento určuje vnější odsazení. Čtení/zápis Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Vrací nebo nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním posunem od pravého okraje ohraničujícího rámečku tvaru. Kladné procento určuje vnitřní odsazení, záporné procento určuje vnější odsazení. Čtení/zápis Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Vrací nebo nastavuje horní okraj výplňového obdélníku, který je definován procentuálním posunem od horního okraje ohraničujícího rámečku tvaru. Kladné procento určuje vnitřní odsazení, záporné procento určuje vnější odsazení. Čtení/zápis Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Vrací nebo nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení ovládá počáteční bod texturové šablony a to, jak se opakuje po celém tvaru. Čtení/zápis [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Překlápí dlaždici textury podél její vodorovné, svislé nebo obou os. Čtení/zápis [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Vrací nebo nastavuje vodorovný posun textury od počátku tvaru v bodech. Kladná hodnota posune texturu doprava, záporná hodnota ji posune doleva. Čtení/zápis Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Vrací nebo nastavuje svislý posun textury od počátku tvaru v bodech. Kladná hodnota posune texturu dolů, záporná hodnota ji posune nahoru. Čtení/zápis Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Vrací nebo nastavuje vodorovné měřítko výplně texturou jako procento. Čtení/zápis Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Vrací nebo nastavuje svislé měřítko výplně texturou jako procento. Čtení/zápis Single. |

## Metody

| Název | Popis |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a určeného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a určeného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Odstraní oříznuté oblasti výplňového obrázku. |

### Viz také

* rozhraní [IFillParamSource](../ifillparamsource)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->