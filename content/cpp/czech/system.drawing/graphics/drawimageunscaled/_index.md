---
title: DrawImageUnscaled()
second_title: Aspose.Slides pro C++ API referenci
description: Vykreslí zadaný obrázek v jeho původní fyzické velikosti na určeném místě.
type: docs
weight: 443
url: /cs/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) metoda

Vykreslí určený obrázek v jeho původní fyzické velikosti na zadaném místě.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| x | int | Souřadnice X levého horního rohu vykreslovaného obrázku |
| y | int | Souřadnice Y levého horního rohu vykreslovaného obrázku |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) metoda

Vykreslí určený obrázek v jeho původní fyzické velikosti na zadaném místě.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| x | int | Souřadnice X levého horního rohu vykreslovaného obrázku |
| y | int | Souřadnice Y levého horního rohu vykreslovaného obrázku |
| width | int | Není použito |
| height | int | Není použito |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) metoda

Vykreslí určený obrázek v jeho původní fyzické velikosti na zadaném místě.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| rect | const [Rectangle](../../rectangle/)\& | Obdélník, který určuje levý horní roh vykreslovaného obrázku. Vlastnosti X a Y obdélníku určují levý horní roh. Hodnoty šířky a výšky jsou ignorovány. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) metoda

Vykreslí určený obrázek v jeho původní fyzické velikosti na zadaném místě.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Obrázek k vykreslení |
| point | const [Point](../../point/)\& | Struktura [Point](../../point/) určující levý horní roh vykreslovaného obrázku. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Image](../../image/)
* Třída [Graphics](../)
* Třída [Rectangle](../../rectangle/)
* Třída [Point](../../point/)
* Jmenný prostor [System::Drawing](../../)
* Library [Aspose.Slides](../../../)