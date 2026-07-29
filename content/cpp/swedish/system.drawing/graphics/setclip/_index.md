---
title: SetClip()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in beskärningsregionen för ritytan som representeras av det aktuella Graphics-objektet till resultatet av den angivna operationen som kombinerar den aktuella beskärningsregionen och den specificerade regionen.
type: docs
weight: 690
url: /sv/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) metod

Ställer in beskärningsregionen för ritytan som representeras av det aktuella [Graphics](../)-objektet till resultatet av den angivna operationen som kombinerar den aktuella beskärningsregionen och den specificerade regionen.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Anger en region att kombinera |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Anger kombineringsoperationen |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) metod

Ställer in beskärningsregionen för ritytan som representeras av det aktuella [Graphics](../)-objektet till resultatet av den angivna operationen som kombinerar den aktuella beskärningsregionen och den specificerade regionen.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Anger en region att kombinera |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Anger kombineringsoperationen |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) metod

Ställer in beskärningsregionen för ritytan som representeras av det aktuella [Graphics](../)-objektet till resultatet av den angivna operationen som kombinerar den aktuella beskärningsregionen och den specificerade regionen.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Anger en region att kombinera |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Anger kombineringsoperationen |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) metod

INTE IMPLEMENTERAT.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) metod

Ställer in beskärningsregionen för ritytan som representeras av det aktuella [Graphics](../)-objektet till resultatet av den angivna operationen som kombinerar den aktuella beskärningsregionen och regionen som anges av en grafikbana.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Anger en region att kombinera |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Anger kombineringsoperationen |

## Se även

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Region](../../region/)
* Klass [Graphics](../)
* Klass [Rectangle](../../rectangle/)
* Klass [RectangleF](../../rectanglef/)
* Klass [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)