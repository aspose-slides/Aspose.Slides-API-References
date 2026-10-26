---
title: Union()
second_title: Aspose.Slides för C++ API-referens
description: Ersätter regionen som representeras av det aktuella objektet med resultatet av unionoperationen mellan denna region och en region som definieras av den angivna rektangeln.
type: docs
weight: 53
url: /sv/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) method

Ersätter regionen som representeras av det aktuella objektet med resultatet av unionen mellan denna region och en region som definieras av den angivna rektangeln.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | En rektangel som definierar en region att förena denna region med |

## Region::Union(const Rectangle\&) method

Ersätter regionen som representeras av det aktuella objektet med resultatet av unionen mellan denna region och en region som definieras av den angivna rektangeln.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | En rektangel som definierar en region att förena denna region med |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) method

Ersätter regionen som representeras av det aktuella objektet med resultatet av unionen mellan denna region och en region som definieras av den angivna sökvägen.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | En sökväg som definierar en region att förena denna region med |

## Region::Union(const SharedPtr\<Region\>\&) method

Ersätter regionen som representeras av det aktuella objektet med resultatet av unionen mellan denna region och den angivna regionen.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | En region att förena denna region med |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [RectangleF](../../rectanglef/)
* Klass [Region](../)
* Klass [Rectangle](../../rectangle/)
* Klass [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)