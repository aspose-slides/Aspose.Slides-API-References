---
title: Intersect()
second_title: Aspose.Slides for C++ API Reference
description: Replaces the region represented by the current object with the result of intersection of this region and a region defined by the specified rectangle.
type: docs
weight: 79
url: /system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) method


Replaces the region represented by the current object with the result of intersection of this region and a region defined by the specified rectangle.

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | A rectangle that defines a region to intersect this region with |

## Region::Intersect(const Rectangle\&) method


Replaces the region represented by the current object with the result of intersection of this region and a region defined by the specified rectangle.

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | A rectangle that defines a region to intersect this region with |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) method


Replaces the region represented by the current object with the result of intersection of this region and a region defined by the specified path.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | A path that defines a region to intersect this region with |

## Region::Intersect(const SharedPtr\<Region\>\&) method


Replaces the region represented by the current object with the result of intersection of this region and the specified region.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | A region to intersect this region with |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)