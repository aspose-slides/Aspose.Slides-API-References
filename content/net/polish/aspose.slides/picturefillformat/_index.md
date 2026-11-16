---
title: PictureFillFormat
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje styl wypełnienia obrazem.
type: docs
weight: 9410
url: /pl/aspose.slides/picturefillformat/
---
## PictureFillFormat klasa

Reprezentuje styl wypełnienia obrazem.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie bazowego interfejsu IPresentationComponent. Read-only [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycinane od dołu obrazu. Read/write Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycinane od lewej strony obrazu. Read/write Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycinane od prawej strony obrazu. Read/write Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycinane od góry obrazu. Read/write Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Zwraca lub ustawia dpi używane do wypełnienia obrazu. Read/write Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Zwraca obraz. Read-only [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Zwraca lub ustawia tryb wypełnienia obrazu. Read/write [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Zwraca lub ustawia dolną krawędź prostokąta wypełnienia, określaną przez offset procentowy od dolnej krawędzi ramki kształtu. Dodatni procent określa wcięcie, ujemny procent określa występ. Read/write Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Zwraca lub ustawia lewą krawędź prostokąta wypełnienia, określaną przez offset procentowy od lewej krawędzi ramki kształtu. Dodatni procent określa wcięcie, ujemny procent określa występ. Read/write Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Zwraca lub ustawia prawą krawędź prostokąta wypełnienia, określaną przez offset procentowy od prawej krawędzi ramki kształtu. Dodatni procent określa wcięcie, ujemny procent określa występ. Read/write Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Zwraca lub ustawia górną krawędź prostokąta wypełnienia, określaną przez offset procentowy od górnej krawędzi ramki kształtu. Dodatni procent określa wcięcie, ujemny procent określa występ. Read/write Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Zwraca lub ustawia sposób wyrównania tekstury w kształcie. To ustawienie kontroluje punkt początkowy wzoru tekstury oraz sposób jego powtarzania w kształcie. Read/write [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Odwraca kafelek tekstury wokół jego osi poziomej, pionowej lub obu. Read/write [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Zwraca lub ustawia poziomy offset tekstury od pochodzenia kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, ujemna wartość przesuwa ją w lewo. Read/write Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Zwraca lub ustawia pionowy offset tekstury od pochodzenia kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, ujemna wartość przesuwa ją w górę. Read/write Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Zwraca lub ustawia poziomą skalę wypełnienia teksturą jako procent. Read/write Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Zwraca lub ustawia pionową skalę wypełnienia teksturą jako procent. Read/write Single. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Kompresuje obraz, zmniejszając jego rozmiar w zależności od rozmiaru kształtu i określonej rozdzielczości. Opcjonalnie usuwa również przycięte obszary. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Kompresuje obraz, zmniejszając jego rozmiar w zależności od rozmiaru kształtu i określonej rozdzielczości. Opcjonalnie usuwa również przycięte obszary. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Usuwa przycięte obszary wypełniającego obrazu. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z określonym obiektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod skrótu. |

### Zobacz także

* klasa [PVIObject](../pviobject)
* interfejs [IPictureFillFormat](../ipicturefillformat)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->