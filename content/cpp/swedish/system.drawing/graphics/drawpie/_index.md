---
title: DrawPie()
second_title: Aspose.Slides för C++ API-referens
description: Ritar den angivna pajen med den angivna pennan på ytan som representeras av det aktuella objektet.
type: docs
weight: 261
url: /sv/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) metod

Ritar den angivna pajen med den angivna pennan på ytan som representeras av det aktuella objektet.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | En penna att använda när pajen ritas |
| x | **int32_t** | X-koordinaten för det övre vänstra hörnet av rektangeln som definierar ellipsen |
| y | **int32_t** | Y-koordinaten för det övre vänstra hörnet av rektangeln som definierar ellipsen |
| width | **int32_t** | Bredden på rektangeln som definierar ellipsen |
| height | **int32_t** | Höjden på rektangeln som definierar ellipsen |
| startAngle | **int32_t** | Vinkel i grader mätt medurs från X-axeln till startpunkten för pajen |
| sweepAngle | **int32_t** | Vinkel i grader mätt medurs från **startAngle** till slutpunkten för pajen |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) metod


Ritar den angivna pajen med den angivna pennan på ytan som representeras av det aktuella objektet.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | En penna att använda när pajen ritas |
| x | **float** | X-koordinaten för det övre vänstra hörnet av rektangeln som definierar ellipsen |
| y | **float** | Y-koordinaten för det övre vänstra hörnet av rektangeln som definierar ellipsen |
| width | **float** | Bredden på rektangeln som definierar ellipsen |
| height | **float** | Höjden på rektangeln som definierar ellipsen |
| startAngle | **float** | Vinkel i grader mätt medurs från X-axeln till startpunkten för pajen |
| sweepAngle | **float** | Vinkel i grader mätt medurs från **startAngle** till slutpunkten för pajen |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) metod


Ritar den angivna pajen med den angivna pennan på ytan som representeras av det aktuella objektet.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | En penna att använda när pajen ritas |
| rect | [Rectangle](../../rectangle/) | Rektangeln som definierar ellipsen |
| startAngle | **float** | Vinkel i grader mätt medurs från X-axeln till startpunkten för pajen |
| sweepAngle | **float** | Vinkel i grader mätt medurs från **startAngle** till slutpunkten för pajen |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) metod


Ritar den angivna pajen med den angivna pennan på ytan som representeras av det aktuella objektet.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | En penna att använda när pajen ritas |
| rect | [RectangleF](../../rectanglef/) | Rektangeln som definierar ellipsen |
| startAngle | **float** | Vinkel i grader mätt medurs från X-axeln till startpunkten för pajen |
| sweepAngle | **float** | Vinkel i grader mätt medurs från **startAngle** till slutpunkten för pajen |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Pen](../../pen/)
* Klass [Graphics](../)
* Klass [Rectangle](../../rectangle/)
* Klass [RectangleF](../../rectanglef/)
* Namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)