---
title: IPictureFillFormat
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Reprezentuje styl wypełnienia obrazem.
type: docs
weight: 6650
url: /pl/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat interfejs

Reprezentuje styl wypełnienia obrazem.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Umożliwia pobranie podstawowego interfejsu IFillParamSource. Tylko do odczytu [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycinane od dołu obrazu. Odczyt/zapis Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycinane od lewej strony obrazu. Odczyt/zapis Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycinane od prawej strony obrazu. Odczyt/zapis Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycinane od górnej krawędzi obrazu. Odczyt/zapis Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Zwraca lub ustawia dpi używane do wypełnienia obrazu. Odczyt/zapis Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Zwraca obraz. Tylko do odczytu [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Zwraca lub ustawia tryb wypełniania obrazu. Odczyt/zapis [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Zwraca lub ustawia dolny brzeg prostokąta wypełnienia określony przez procentowy offset od dolnego brzegu ramki kształtu. Dodatni procent określa wcięcie, natomiast ujemny procent określa występ. Odczyt/zapis Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Zwraca lub ustawia lewy brzeg prostokąta wypełnienia określony przez procentowy offset od lewego brzegu ramki kształtu. Dodatni procent określa wcięcie, natomiast ujemny procent określa występ. Odczyt/zapis Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Zwraca lub ustawia prawy brzeg prostokąta wypełnienia określony przez procentowy offset od prawego brzegu ramki kształtu. Dodatni procent określa wcięcie, natomiast ujemny procent określa występ. Odczyt/zapis Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Zwraca lub ustawia górny brzeg prostokąta wypełnienia określony przez procentowy offset od górnego brzegu ramki kształtu. Dodatni procent określa wcięcie, natomiast ujemny procent określa występ. Odczyt/zapis Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Zwraca lub ustawia sposób wyrównania tekstury w obrębie kształtu. To ustawienie kontroluje punkt początkowy wzoru tekstury i sposób jego powtarzania w kształcie. Odczyt/zapis [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Odwraca kafelki tekstury wokół jego osi poziomej, pionowej lub obu. Odczyt/zapis [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Zwraca lub ustawia poziomy offset tekstury od początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, natomiast ujemna w lewo. Odczyt/zapis Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Zwraca lub ustawia pionowy offset tekstury od początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, natomiast ujemna w górę. Odczyt/zapis Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Zwraca lub ustawia poziomą skalę wypełnienia teksturą jako procent. Odczyt/zapis Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Zwraca lub ustawia pionową skalę wypełnienia teksturą jako procent. Odczyt/zapis Single. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Kompresuje obraz, zmniejszając jego rozmiar w oparciu o rozmiar kształtu i określoną rozdzielczość. Opcjonalnie usuwa także przycięte obszary. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Kompresuje obraz, zmniejszając jego rozmiar w oparciu o rozmiar kształtu i określoną rozdzielczość. Opcjonalnie usuwa także przycięte obszary. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Usuwa przycięte obszary obrazu wypełnienia. |

### Zobacz także

* interfejs [IFillParamSource](../ifillparamsource)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->