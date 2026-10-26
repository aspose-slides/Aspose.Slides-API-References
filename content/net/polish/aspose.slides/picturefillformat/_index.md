---
title: PictureFillFormat
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje styl wypełnienia obrazem.
type: docs
weight: 9390
url: /pl/aspose.slides/picturefillformat/
---
## PictureFillFormat class

Reprezentuje styl wypełnienia obrazem.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Properties

| Nazwa | Opis |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie podstawowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte od dołu obrazu. Odczyt/zapis Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte od lewej strony obrazu. Odczyt/zapis Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte od prawej strony obrazu. Odczyt/zapis Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte od góry obrazu. Odczyt/zapis Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Zwraca lub ustawia DPI używane do wypełniania obrazem. Odczyt/zapis Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Zwraca obraz. Tylko do odczytu [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Zwraca lub ustawia tryb wypełnienia obrazem. Odczyt/zapis [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Zwraca lub ustawia dolną krawędź prostokąta wypełnienia określoną jako procentowy offset od dolnej krawędzi ramki kształtu. Dodatni procent oznacza wcięcie, ujemny – występ. Odczyt/zapis Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Zwraca lub ustawia lewą krawędź prostokąta wypełnienia określoną jako procentowy offset od lewej krawędzi ramki kształtu. Dodatni procent oznacza wcięcie, ujemny – występ. Odczyt/zapis Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Zwraca lub ustawia prawą krawędź prostokąta wypełnienia określoną jako procentowy offset od prawej krawędzi ramki kształtu. Dodatni procent oznacza wcięcie, ujemny – występ. Odczyt/zapis Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Zwraca lub ustawia górną krawędź prostokąta wypełnienia określoną jako procentowy offset od górnej krawędzi ramki kształtu. Dodatni procent oznacza wcięcie, ujemny – występ. Odczyt/zapis Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Zwraca lub ustawia sposób wyrównania tekstury wewnątrz kształtu. Ustawienie określa punkt początkowy wzoru tekstury i sposób jego powtarzania w kształcie. Odczyt/zapis [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Obraca kafelek tekstury wokół osi poziomej, pionowej lub obu. Odczyt/zapis [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Zwraca lub ustawia poziomy offset tekstury od początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, ujemna w lewo. Odczyt/zapis Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Zwraca lub ustawia pionowy offset tekstury od początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, ujemna w górę. Odczyt/zapis Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Zwraca lub ustawia poziomą skalę wypełnienia teksturą jako procent. Odczyt/zapis Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Zwraca lub ustawia pionową skalę wypełnienia teksturą jako procent. Odczyt/zapis Single. |

## Methods

| Nazwa | Opis |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Kompresuje obraz, zmniejszając jego rozmiar w oparciu o rozmiar kształtu i określoną rozdzielczość. Opcjonalnie usuwa również przycięte obszary. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Kompresuje obraz, zmniejszając jego rozmiar w oparciu o rozmiar kształtu i określoną rozdzielczość. Opcjonalnie usuwa również przycięte obszary. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Usuwa przycięte obszary obrazu wypełnienia. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z podanym obiektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod skrótu. |

### See Also

* klasa [PVIObject](../pviobject)
* interfejs [IPictureFillFormat](../ipicturefillformat)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->