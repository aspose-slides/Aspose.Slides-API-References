---
title: PictureFillFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Představuje styl výplně obrázkem.
type: docs
weight: 9410
url: /cs/aspose.slides/picturefillformat/
---
## třída PictureFillFormat

Představuje styl výplně obrázkem.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Vlastnosti

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, který je oříznut odspodu obrázku. Čtení/zápis Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, který je oříznut zleva obrázku. Čtení/zápis Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Vrací nebo nastavuje počet procent skutečné šířky obrázku, který je oříznut zprava obrázku. Čtení/zápis Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Vrací nebo nastavuje počet procent skutečné výšky obrázku, který je oříznut od vrchu obrázku. Čtení/zápis Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Vrací nebo nastavuje DPI, které se používá k výplni obrázku. Čtení/zápis Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Vrací obrázek. Pouze pro čtení [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Vrací nebo nastavuje režim výplně obrázku. Čtení/zápis [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Vrací nebo nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním posunem od spodního okraje ohraničovacího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento udává vnější odsazení. Čtení/zápis Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Vrací nebo nastavuje levý okraj výplňového obdélníku, který je definován procentuálním posunem od levého okraje ohraničovacího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento udává vnější odsazení. Čtení/zápis Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Vrací nebo nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním posunem od pravého okraje ohraničovacího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento udává vnější odsazení. Čtení/zápis Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Vrací nebo nastavuje horní okraj výplňového obdélníku, který je definován procentuálním posunem od horního okraje ohraničovacího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento udává vnější odsazení. Čtení/zápis Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Vrací nebo nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí počáteční bod vzoru textury a to, jak se opakuje po celém tvaru. Čtení/zápis [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Překlápí dlaždici textury podél její horizontální, vertikální nebo obou os. Čtení/zápis [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Vrací nebo nastavuje horizontální posun textury od počátku tvaru v bodech. Kladná hodnota posune texturu doprava, záporná hodnota ji posune doleva. Čtení/zápis Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Vrací nebo nastavuje vertikální posun textury od počátku tvaru v bodech. Kladná hodnota posune texturu dolů, záporná hodnota ji posune nahoru. Čtení/zápis Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Vrací nebo nastavuje horizontální měřítko výplně textury v procentech. Čtení/zápis Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Vrací nebo nastavuje vertikální měřítko výplně textury v procentech. Čtení/zápis Single. |

## Metody

| Name | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Odstraňuje oříznuté oblasti výplňového obrázku. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává se zadaným objektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Viz také

* třída [PVIObject](../pviobject)
* rozhraní [IPictureFillFormat](../ipicturefillformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->