---
title: IsVisible()
second_title: Aspose.Slides for C++ API Reference
description: Determines if the specified point is contained within the region represented by the current object.
type: docs
weight: 196
url: /system.drawing/region/isvisible/
---
## Region::IsVisible(const Point\&) const method


Determines if the specified point is contained within the region represented by the current object.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [Point](../../point/)\& | The point to check |

## Region::IsVisible(const PointF\&) const method


Determines if the specified point is contained within the region represented by the current object.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | The point to check |

## Region::IsVisible(const Rectangle\&) method


Determines if any portion the specified rectangle is contained within the region represented by the current object.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | The rectangle to check |

## Region::IsVisible(const RectangleF\&) method


Determines if any portion the specified rectangle is contained within the region represented by the current object.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | The rectangle to check |

## Region::IsVisible(const Point\&, const SharedPtr\<Graphics\>\&) const method


Determines if the specified point is contained within the region represented by the current object using the specified graphics.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point, const SharedPtr<Graphics> &graphics) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [Point](../../point/)\& | The point to check |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | The graphics context |

## Region::IsVisible(const PointF\&, const SharedPtr\<Graphics\>\&) const method


Determines if the specified point is contained within the region represented by the current object using the specified graphics.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point, const SharedPtr<Graphics> &graphics) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | The point to check |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | The graphics context |

## Region::IsVisible(const Rectangle\&, const SharedPtr\<Graphics\>\&) method


Determines if any portion the specified rectangle is contained within the region represented by the current object using the specified graphics.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect, const SharedPtr<Graphics> &graphics)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | The rectangle to check |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | The graphics context |

## Region::IsVisible(const RectangleF\&, const SharedPtr\<Graphics\>\&) method


Determines if any portion the specified rectangle is contained within the region represented by the current object using the specified graphics.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect, const SharedPtr<Graphics> &graphics)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | The rectangle to check |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | The graphics context |

## Region::IsVisible(float, float) const method


Determines if the specified point is contained within the region represented by the current object.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The X coordinate of the point to check |
| y | **float** | The Y coordinate of the point to check |

## Region::IsVisible(float, float, const SharedPtr\<Graphics\>\&) const method


Determines if the specified point is contained within the region represented by the current object using the specified graphics.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y, const SharedPtr<Graphics> &graphics) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The X coordinate of the point to check |
| y | **float** | The Y coordinate of the point to check |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | The graphics context |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Point](../../point/)
* Class [Region](../)
* Class [PointF](../../pointf/)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)