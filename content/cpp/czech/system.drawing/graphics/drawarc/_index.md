---
title: DrawArc()
second_title: Aspose.Slides pro C++ referenční příručka
description: Vykreslí zadaný oblouk pomocí zadaného pera na povrchu představovaném aktuálním objektem.
type: docs
weight: 248
url: /cs/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) metoda


Vykreslí zadaný oblouk pomocí zadaného pera na povrchu představovaném aktuálním objektem.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při vykreslování oblouku |
| x | **int32_t** | X-souřadnice levého horního rohu obdélníku, který definuje elipsu |
| y | **int32_t** | Y-souřadnice levého horního rohu obdélníku, který definuje elipsu |
| width | **int32_t** | Šířka obdélníku, který definuje elipsu |
| height | **int32_t** | Výška obdélníku, který definuje elipsu |
| startAngle | **int32_t** | Úhel ve stupních měřený po směru hodinových ručiček od osy X k výchozímu bodu oblouku |
| sweepAngle | **int32_t** | Úhel ve stupních měřený po směru hodinových ručiček od **startAngle** k koncovému bodu oblouku |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) metoda


Vykreslí zadaný oblouk pomocí zadaného pera na povrchu představovaném aktuálním objektem.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při vykreslování oblouku |
| x | **float** | X-souřadnice levého horního rohu obdélníku, který definuje elipsu |
| y | **float** | Y-souřadnice levého horního rohu obdélníku, který definuje elipsu |
| width | **float** | Šířka obdélníku, který definuje elipsu |
| height | **float** | Výška obdélníku, který definuje elipsu |
| startAngle | **float** | Úhel ve stupních měřený po směru hodinových ručiček od osy X k výchozímu bodu oblouku |
| sweepAngle | **float** | Úhel ve stupních měřený po směru hodinových ručiček od **startAngle** k koncovému bodu oblouku |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) metoda


Vykreslí zadaný oblouk pomocí zadaného pera na povrchu představovaném aktuálním objektem.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při vykreslování oblouku |
| rect | [Rectangle](../../rectangle/) | Obdélník, který definuje elipsu |
| startAngle | **float** | Úhel ve stupních měřený po směru hodinových ručiček od osy X k výchozímu bodu oblouku |
| sweepAngle | **float** | Úhel ve stupních měřený po směru hodinových ručiček od **startAngle** k koncovému bodu oblouku |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) metoda


Vykreslí zadaný oblouk pomocí zadaného pera na povrchu představovaném aktuálním objektem.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při vykreslování oblouku |
| rect | [RectangleF](../../rectanglef/) | Obdélník, který definuje elipsu |
| startAngle | **float** | Úhel ve stupních měřený po směru hodinových ručiček od osy X k výchozímu bodu oblouku |
| sweepAngle | **float** | Úhel ve stupních měřený po směru hodinových ručiček od **startAngle** k koncovému bodu oblouku |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [Pen](../../pen/)
* třída [Graphics](../)
* třída [Rectangle](../../rectangle/)
* třída [RectangleF](../../rectanglef/)
* jmenný prostor [System::Drawing](../../)
* knihovna [Aspose.Slides](../../../)