---
title: DrawArc()
second_title: Aspose.Slides dla C++ – referencja API
description: Rysuje określony łuk przy użyciu określonego pióra na powierzchni reprezentowanej przez bieżący obiekt.
type: docs
weight: 248
url: /pl/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) metoda


Rysuje określony łuk przy użyciu określonego pióra na powierzchni reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pióro używane przy rysowaniu łuku |
| x | **int32_t** | Współrzędna X lewego górnego rogu prostokąta definiującego elipsę |
| y | **int32_t** | Współrzędna Y lewego górnego rogu prostokąta definiującego elipsę |
| width | **int32_t** | Szerokość prostokąta definiującego elipsę |
| height | **int32_t** | Wysokość prostokąta definiującego elipsę |
| startAngle | **int32_t** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od osi X do punktu początkowego łuku |
| sweepAngle | **int32_t** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od **startAngle** do punktu końcowego łuku |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) metoda


Rysuje określony łuk przy użyciu określonego pióra na powierzchni reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pióro używane przy rysowaniu łuku |
| x | **float** | Współrzędna X lewego górnego rogu prostokąta definiującego elipsę |
| y | **float** | Współrzędna Y lewego górnego rogu prostokąta definiującego elipsę |
| width | **float** | Szerokość prostokąta definiującego elipsę |
| height | **float** | Wysokość prostokąta definiującego elipsę |
| startAngle | **float** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od osi X do punktu początkowego łuku |
| sweepAngle | **float** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od **startAngle** do punktu końcowego łuku |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) metoda


Rysuje określony łuk przy użyciu określonego pióra na powierzchni reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pióro używane przy rysowaniu łuku |
| rect | [Rectangle](../../rectangle/) | Prostokąt definiujący elipsę |
| startAngle | **float** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od osi X do punktu początkowego łuku |
| sweepAngle | **float** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od **startAngle** do punktu końcowego łuku |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) metoda


Rysuje określony łuk przy użyciu określonego pióra na powierzchni reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pióro używane przy rysowaniu łuku |
| rect | [RectangleF](../../rectanglef/) | Prostokąt definiujący elipsę |
| startAngle | **float** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od osi X do punktu początkowego łuku |
| sweepAngle | **float** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od **startAngle** do punktu końcowego łuku |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Pen](../../pen/)
* Klasa [Graphics](../)
* Klasa [Rectangle](../../rectangle/)
* Klasa [RectangleF](../../rectanglef/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)