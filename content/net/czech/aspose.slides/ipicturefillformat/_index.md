---
title: IPictureFillFormat
second_title: Aspose.Sildes pro .NET – referenční dokumentace API
description: Zastupuje styl výplně obrázkem.
type: docs
weight: 6650
url: /cs/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat rozhraní

Zastupuje styl výplně obrázkem.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Umožňuje získat základní rozhraní IFillParamSource. Pouze ke čtení [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, která je oříznuta ze spodní části obrázku. Čtení/Zápis Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, která je oříznuta z levé strany obrázku. Čtení/Zápis Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, která je oříznuta z pravé strany obrázku. Čtení/Zápis Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, která je oříznuta z horní části obrázku. Čtení/Zápis Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Vrací nebo nastavuje dpi, které se používá k vyplnění obrázku. Čtení/Zápis Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Vrací obrázek. Pouze ke čtení [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Vrací nebo nastavuje režim výplně obrázkem. Čtení/Zápis [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Vrací nebo nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním posunem od spodního okraje ohraničujícího rámečku tvaru. Kladné procento určuje vtah, zatímco záporné procento určuje výstupek. Čtení/Zápis Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Vrací nebo nastavuje levý okraj výplňového obdélníku, který je definován procentuálním posunem od levého okraje ohraničujícího rámečku tvaru. Kladné procento určuje vtah, zatímco záporné procento určuje výstupek. Čtení/Zápis Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Vrací nebo nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním posunem od pravého okraje ohraničujícího rámečku tvaru. Kladné procento určuje vtah, zatímco záporné procento určuje výstupek. Čtení/Zápis Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Vrací nebo nastavuje horní okraj výplňového obdélníku, který je definován procentuálním posunem od horního okraje ohraničujícího rámečku tvaru. Kladné procento určuje vtah, zatímco záporné procento určuje výstupek. Čtení/Zápis Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Vrací nebo nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí výchozí bod vzoru textury a to, jak se opakuje po celém tvaru. Čtení/Zápis [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Překlápí dlaždici textury podél její vodorovné, svislé nebo obou os. Čtení/Zápis [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Vrací nebo nastavuje vodorovný posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, záporná hodnota ji posouvá doleva. Čtení/Zápis Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Vrací nebo nastavuje svislý posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, záporná ji posouvá nahoru. Čtení/Zápis Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Vrací nebo nastavuje vodorovné měřítko výplně texturou v procentech. Čtení/Zápis Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Vrací nebo nastavuje svislé měřítko výplně texturou v procentech. Čtení/Zápis Single. |

## Metody

| Název | Popis |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Odstraní oříznuté oblasti výplňového obrázku. |

### Viz také

* rozhraní [IFillParamSource](../ifillparamsource)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->