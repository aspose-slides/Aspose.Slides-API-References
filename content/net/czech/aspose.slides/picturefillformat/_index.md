---
title: PictureFillFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Představuje styl výplně obrázkem.
type: docs
weight: 9370
url: /cs/aspose.slides/picturefillformat/
---
## PictureFillFormat třída

Representuje styl výplně obrázkem.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty ze spodní části obrázku. Čtení/Zápis Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z levé strany obrázku. Čtení/Zápis Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z pravé strany obrázku. Čtení/Zápis Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty z horní části obrázku. Čtení/Zápis Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Vrací nebo nastavuje dpi, které se používá k výplni obrázkem. Čtení/Zápis Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Vrací obrázek. Pouze pro čtení [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Vrací nebo nastavuje režim výplně obrázkem. Čtení/Zápis [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Vrací nebo nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním posunem od spodního okraje ohraničujícího rámečku tvaru. Kladné procento určuje vnitřní odsazení, záporné procento určuje vnější odsazení. Čtení/Zápis Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Vrací nebo nastavuje levý okraj výplňového obdélníku, který je definován procentuálním posunem od levého okraje ohraničujícího rámečku tvaru. Kladné procento určuje vnitřní odsazení, záporné procento určuje vnější odsazení. Čtení/Zápis Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Vrací nebo nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním posunem od pravého okraje ohraničujícího rámečku tvaru. Kladné procento určuje vnitřní odsazení, záporné procento určuje vnější odsazení. Čtení/Zápis Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Vrací nebo nastavuje horní okraj výplňového obdélníku, který je definován procentuálním posunem od horního okraje ohraničujícího rámečku tvaru. Kladné procento určuje vnitřní odsazení, záporné procento určuje vnější odsazení. Čtení/Zápis Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Vrací nebo nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí výchozí bod vzoru textury a to, jak se opakuje po tvaru. Čtení/Zápis [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Otáčí dlaždici textury kolem horizontální, vertikální nebo obou os. Čtení/Zápis [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Vrací nebo nastavuje vodorovný posun textury od počátku tvaru v bodech. Kladná hodnota posune texturu doprava, záporná hodnota posune texturu doleva. Čtení/Zápis Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Vrací nebo nastavuje svislý posun textury od počátku tvaru v bodech. Kladná hodnota posune texturu dolů, záporná hodnota posune texturu nahoru. Čtení/Zápis Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Vrací nebo nastavuje vodorovné měřítko výplně textury v procentech. Čtení/Zápis Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Vrací nebo nastavuje svislé měřítko výplně textury v procentech. Čtení/Zápis Single. |

## Metody

| Název | Popis |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Komprimuje obrázek zmenšením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimuje obrázek zmenšením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Odstraní oříznuté oblasti výplňového obrázku. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovná s určeným objektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Viz také

* třída [PVIObject](../pviobject)
* rozhraní [IPictureFillFormat](../ipicturefillformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->