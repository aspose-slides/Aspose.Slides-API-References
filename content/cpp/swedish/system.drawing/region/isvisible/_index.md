---
title: IsVisible()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet.
type: docs
weight: 196
url: /sv/system.drawing/region/isvisible/
---
## Region::IsVisible(const Point\&) const metod


Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | const [Point](../../point/)\& | Punkten som ska kontrolleras |

## Region::IsVisible(const PointF\&) const metod


Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | Punkten som ska kontrolleras |

## Region::IsVisible(const Rectangle\&) metod


Avgör om någon del av den angivna rektangeln finns inom regionen som representeras av det aktuella objektet.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Rektangeln som ska kontrolleras |

## Region::IsVisible(const RectangleF\&) metod


Avgör om någon del av den angivna rektangeln finns inom regionen som representeras av det aktuella objektet.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Rektangeln som ska kontrolleras |

## Region::IsVisible(const Point\&, const SharedPtr\<Graphics\>\&) const metod


Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet med den angivna grafik-kontexten.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point, const SharedPtr<Graphics> &graphics) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | const [Point](../../point/)\& | Punkten som ska kontrolleras |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Grafikkontexten |

## Region::IsVisible(const PointF\&, const SharedPtr\<Graphics\>\&) const metod


Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet med den angivna grafik-kontexten.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point, const SharedPtr<Graphics> &graphics) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | Punkten som ska kontrolleras |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Grafikkontexten |

## Region::IsVisible(const Rectangle\&, const SharedPtr\<Graphics\>\&) metod


Avgör om någon del av den angivna rektangeln finns inom regionen som representeras av det aktuella objektet med den angivna grafik-kontexten.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect, const SharedPtr<Graphics> &graphics)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Rektangeln som ska kontrolleras |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Grafikkontexten |

## Region::IsVisible(const RectangleF\&, const SharedPtr\<Graphics\>\&) metod


Avgör om någon del av den angivna rektangeln finns inom regionen som representeras av det aktuella objektet med den angivna grafik-kontexten.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect, const SharedPtr<Graphics> &graphics)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Rektangeln som ska kontrolleras |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Grafikkontexten |

## Region::IsVisible(float, float) const metod


Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för punkten som ska kontrolleras |
| y | **float** | Y-koordinaten för punkten som ska kontrolleras |

## Region::IsVisible(float, float, const SharedPtr\<Graphics\>\&) const metod


Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet med den angivna grafik-kontexten.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y, const SharedPtr<Graphics> &graphics) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | X-koordinaten för punkten som ska kontrolleras |
| y | **float** | Y-koordinaten för punkten som ska kontrolleras |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Grafikkontexten |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Point](../../point/)
* Class [Region](../)
* Class [PointF](../../pointf/)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)