---
title: Exclude()
second_title: Aspose.Slides för C++ API-referens
description: Ersätter den region som representeras av det aktuella objektet med resultatet av uteslutning av den region som definieras av den angivna rektangeln från den.
type: docs
weight: 92
url: /sv/system.drawing/region/exclude/
---
## Region::Exclude(const RectangleF\&) metod

Ersätter den region som representeras av det aktuella objektet med resultatet av uteslutning av den region som definieras av den angivna rektangeln från den.

```cpp
void System::Drawing::Region::Exclude(const RectangleF &rect)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | En rektangel som definierar en region att utesluta |

## Region::Exclude(const Rectangle\&) metod

Ersätter den region som representeras av det aktuella objektet med resultatet av uteslutning av den region som definieras av den angivna rektangeln från den.

```cpp
void System::Drawing::Region::Exclude(const Rectangle &rect)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | En rektangel som definierar en region att utesluta |

## Region::Exclude(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metod

Ersätter den region som representeras av det aktuella objektet med resultatet av uteslutning av den region som definieras av den angivna vägen från den.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | En väg som definierar en region att utesluta |

## Region::Exclude(const SharedPtr\<Region\>\&) metod

Ersätter den region som representeras av det aktuella objektet med resultatet av uteslutning av den angivna regionen från den.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Region> &region)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | En region att utesluta |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)