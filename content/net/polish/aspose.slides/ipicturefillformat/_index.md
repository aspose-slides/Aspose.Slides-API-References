---
title: IPictureFillFormat
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Reprezentuje styl wypełniania obrazem.
type: docs
weight: 6630
url: /pl/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat interfejs

Reprezentuje styl wypełniania obrazem.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Umożliwia pobranie podstawowego interfejsu IFillParamSource. Tylko do odczytu [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte od dołu obrazu. Odczyt/zapis Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte od lewej strony obrazu. Odczyt/zapis Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte od prawej strony obrazu. Odczyt/zapis Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte od górnej części obrazu. Odczyt/zapis Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Zwraca lub ustawia DPI używane do wypełniania obrazu. Odczyt/zapis Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Zwraca obraz. Tylko do odczytu [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Zwraca lub ustawia tryb wypełniania obrazu. Odczyt/zapis [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Zwraca lub ustawia dolną krawędź prostokąta wypełnienia określoną procentowym przesunięciem od dolnej krawędzi ramki kształtu. Dodatni procent określa wcięcie, a ujemny procent określa występ. Odczyt/zapis Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Zwraca lub ustawia lewą krawędź prostokąta wypełnienia określoną procentowym przesunięciem od lewej krawędzi ramki kształtu. Dodatni procent określa wcięcie, a ujemny procent określa występ. Odczyt/zapis Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Zwraca lub ustawia prawą krawędź prostokąta wypełnienia określoną procentowym przesunięciem od prawej krawędzi ramki kształtu. Dodatni procent określa wcięcie, a ujemny procent określa występ. Odczyt/zapis Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Zwraca lub ustawia górną krawędź prostokąta wypełnienia określoną procentowym przesunięciem od górnej krawędzi ramki kształtu. Dodatni procent określa wcięcie, a ujemny procent określa występ. Odczyt/zapis Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Zwraca lub ustawia sposób wyrównania tekstury w kształcie. To ustawienie kontroluje punkt początkowy wzoru tekstury i sposób jego powtarzania w kształcie. Odczyt/zapis [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Odwraca płytkę tekstury wzdłuż jej osi poziomej, pionowej lub obu osi. Odczyt/zapis [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Zwraca lub ustawia poziome przesunięcie tekstury względem początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, a ujemna w lewo. Odczyt/zapis Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Zwraca lub ustawia pionowe przesunięcie tekstury względem początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, a ujemna w górę. Odczyt/zapis Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Zwraca lub ustawia poziomą skalę wypełnienia teksturą jako procent. Odczyt/zapis Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Zwraca lub ustawia pionową skalę wypełnienia teksturą jako procent. Odczyt/zapis Single. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Kompresuje obraz poprzez zmniejszenie jego rozmiaru w oparciu o wielkość kształtu i określoną rozdzielczość. Opcjonalnie usuwa również przycięte obszary. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Kompresuje obraz poprzez zmniejszenie jego rozmiaru w oparciu o wielkość kształtu i określoną rozdzielczość. Opcjonalnie usuwa również przycięte obszary. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Usuwa przycięte obszary obrazu wypełnienia. |

### Zobacz także

* interfejs [IFillParamSource](../ifillparamsource)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->