---
title: Union()
second_title: Aspose.Slides for C++ API Reference
description: Replaces the region represented by the current object with the result of union operation of this region and a region defined by the specified rectangle.
type: docs
weight: 53
url: /cpp/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) method


Replaces the region represented by the current object with the result of union operation of this region and a region defined by the specified rectangle.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | A rectangle that defines a region to unite this region with |

## Region::Union(const Rectangle\&) method


Replaces the region represented by the current object with the result of union of this region and a region defined by the specified rectangle.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | A rectangle that defines a region to unite this region with |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) method


Replaces the region represented by the current object with the result of union of this region and a region defined by the specified path.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | A path that defines a region to unite this region with |

## Region::Union(const SharedPtr\<Region\>\&) method


Replaces the region represented by the current object with the result of union of this region and and the specified region.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | A region to unite this region with |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)