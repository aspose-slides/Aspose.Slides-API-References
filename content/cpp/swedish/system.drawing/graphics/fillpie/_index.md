---
title: FillPie()
second_title: Aspose.Slides för C++ API-referens
description: Fyller den angivna pajen med den angivna penseln på ytan som representeras av det aktuella objektet.
type: docs
weight: 274
url: /sv/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) metod

Fyller den angivna pajen med den angivna penseln på ytan som representeras av det aktuella objektet.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | En pensel att använda när pajen fylls |
| x | int | X-koordinaten för det övre vänstra hörnet på rektangeln som definierar ellipsen |
| y | int | Y-koordinaten för det övre vänstra hörnet på rektangeln som definierar ellipsen |
| width | int | Bredden på rektangeln som definierar ellipsen |
| height | int | Höjden på rektangeln som definierar ellipsen |
| startAngle | int | Vinkel i grader mätt medurs från X-axeln till startpunkten för pajen |
| sweepAngle | int | Vinkel i grader mätt medurs från **startAngle** till slutpunkten för pajen |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) metod

Fyller den angivna pajen med den angivna penseln på ytan som representeras av det aktuella objektet.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | En pensel att använda när pajen fylls |
| x | **float** | X-koordinaten för det övre vänstra hörnet på rektangeln som definierar ellipsen |
| y | **float** | Y-koordinaten för det övre vänstra hörnet på rektangeln som definierar ellipsen |
| width | **float** | Bredden på rektangeln som definierar ellipsen |
| height | **float** | Höjden på rektangeln som definierar ellipsen |
| startAngle | **float** | Vinkel i grader mätt medurs från X-axeln till startpunkten för pajen |
| sweepAngle | **float** | Vinkel i grader mätt medurs från **startAngle** till slutpunkten för pajen |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) metod

Fyller den angivna pajen med den angivna penseln på ytan som representeras av det aktuella objektet.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | En pensel att använda när pajen fylls |
| rect | [Rectangle](../../rectangle/) | Rektangeln som definierar ellipsen |
| startAngle | **float** | Vinkel i grader mätt medurs från X-axeln till startpunkten för pajen |
| sweepAngle | **float** | Vinkel i grader mätt medurs från **startAngle** till slutpunkten för pajen |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Brush](../../brush/)
* Klass [Graphics](../)
* Klass [Rectangle](../../rectangle/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)