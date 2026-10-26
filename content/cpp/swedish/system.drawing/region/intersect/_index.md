---
title: Intersect()
second_title: Aspose.Slides för C++ API-referens
description: Ersätter regionen som representeras av det aktuella objektet med resultatet av skärningen mellan denna region och en region som definieras av den angivna rektangeln.
type: docs
weight: 79
url: /sv/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) metod


Ersätter regionen som representeras av det aktuella objektet med resultatet av skärningen mellan denna region och en region som definieras av den angivna rektangeln.

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | En rektangel som definierar en region att skära denna region med |

## Region::Intersect(const Rectangle\&) metod


Ersätter regionen som representeras av det aktuella objektet med resultatet av skärningen mellan denna region och en region som definieras av den angivna rektangeln.

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | En rektangel som definierar en region att skära denna region med |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metod


Ersätter regionen som representeras av det aktuella objektet med resultatet av skärningen mellan denna region och en region som definieras av den angivna banan.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | En bana som definierar en region att skära denna region med |

## Region::Intersect(const SharedPtr\<Region\>\&) metod


Ersätter regionen som representeras av det aktuella objektet med resultatet av skärningen mellan denna region och den angivna regionen.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | En region att skära denna region med |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [RectangleF](../../rectanglef/)
* Klass [Region](../)
* Klass [Rectangle](../../rectangle/)
* Klass [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)