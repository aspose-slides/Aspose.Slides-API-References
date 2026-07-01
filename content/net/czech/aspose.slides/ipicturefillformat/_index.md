---
title: IPictureFillFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Představuje styl výplně obrázkem.
type: docs
weight: 6630
url: /cs/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat rozhraní

Představuje styl výplně obrázkem.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Umožňuje získat základní rozhraní IFillParamSource. Pouze pro čtení [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, který je oříznut od spodní části obrázku. Čtení/Zápis Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, který je oříznut od levé strany obrázku. Čtení/Zápis Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, který je oříznut od pravé strany obrázku. Čtení/Zápis Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, který je oříznut od horní části obrázku. Čtení/Zápis Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Vrací nebo nastavuje dpi, které je použito k vyplnění obrázku. Čtení/Zápis Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Vrací obrázek. Pouze pro čtení [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Vrací nebo nastavuje režim výplně obrázku. Čtení/Zápis [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Vrací nebo nastavuje spodní okraj výplňového obdélníku definovaného procentuálním posunem od spodního okraje ohraničujícího rámečku tvaru. Kladné procento specifikuje vnitřní odsazení, záporné procento vnější odsazení. Čtení/Zápis Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Vrací nebo nastavuje levý okraj výplňového obdélníku definovaného procentuálním posunem od levého okraje ohraničujícího rámečku tvaru. Kladné procento specifikuje vnitřní odsazení, záporné procento vnější odsazení. Čtení/Zápis Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Vrací nebo nastavuje pravý okraj výplňového obdélníku definovaného procentuálním posunem od pravého okraje ohraničujícího rámečku tvaru. Kladné procento specifikuje vnitřní odsazení, záporné procento vnější odsazení. Čtení/Zápis Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Vrací nebo nastavuje horní okraj výplňového obdélníku definovaného procentuálním posunem od horního okraje ohraničujícího rámečku tvaru. Kladné procento specifikuje vnitřní odsazení, záporné procento vnější odsazení. Čtení/Zápis Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Vrací nebo nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení určuje výchozí bod vzoru textury a způsob, jakým se opakuje po celém tvaru. Čtení/Zápis [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Otočí dlaždici textury kolem její horizontální, vertikální nebo obou os. Čtení/Zápis [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Vrací nebo nastavuje horizontální posun textury od počátku tvaru v bodech. Kladná hodnota posune texturu doprava, záporná hodnota posune texturu doleva. Čtení/Zápis Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Vrací nebo nastavuje vertikální posun textury od počátku tvaru v bodech. Kladná hodnota posune texturu dolů, záporná hodnota posune texturu nahoru. Čtení/Zápis Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Vrací nebo nastavuje horizontální měřítko výplně textury jako procento. Čtení/Zápis Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Vrací nebo nastavuje vertikální měřítko výplně textury jako procento. Čtení/Zápis Single. |

## Metody

| Název | Popis |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Odstraňuje oříznuté oblasti výplňového obrázku. |

### Viz také

* rozhraní [IFillParamSource](../ifillparamsource)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->