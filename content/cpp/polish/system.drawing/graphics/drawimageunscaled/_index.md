---
title: DrawImageUnscaled()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Rysuje określony obraz, używając jego pierwotnego rozmiaru fizycznego w podanej lokalizacji.
type: docs
weight: 443
url: /pl/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) metoda

Rysuje określony obraz, używając jego pierwotnego rozmiaru fizycznego w podanej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| x | int | Współrzędna X lewego górnego rogu rysowanego obrazu |
| y | int | Współrzędna Y lewego górnego rogu rysowanego obrazu |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) metoda

Rysuje określony obraz, używając jego pierwotnego rozmiaru fizycznego w podanej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| x | int | Współrzędna X lewego górnego rogu rysowanego obrazu |
| y | int | Współrzędna Y lewego górnego rogu rysowanego obrazu |
| width | int | Nie używane |
| height | int | Nie używane |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) metoda

Rysuje określony obraz, używając jego pierwotnego rozmiaru fizycznego w podanej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| rect | const [Rectangle](../../rectangle/)\& | Prostokąt określający lewy górny róg rysowanego obrazu. Właściwości X i Y prostokąta określają lewy górny róg. Wartości szerokości i wysokości są ignorowane. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) metoda

Rysuje określony obraz, używając jego pierwotnego rozmiaru fizycznego w podanej lokalizacji.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obraz do narysowania |
| point | const [Point](../../point/)\& | Struktura [Point](../../point/) określająca lewy górny róg rysowanego obrazu. |

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Image](../../image/)
* Klasa [Graphics](../)
* Klasa [Rectangle](../../rectangle/)
* Klasa [Point](../../point/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)