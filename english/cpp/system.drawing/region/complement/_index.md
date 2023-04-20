---
title: Complement()
second_title: Aspose.Slides for C++ API Reference
description: Replaces the region represented by the current object with the portion of the region defined by the specified recangle that does not intersect with this region.
type: docs
weight: 131
url: /cpp/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) method


Replaces the region represented by the current object with the portion of the region defined by the specified recangle that does not intersect with this region.

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | A rectangle that defines a region to complement |

## Region::Complement(const Rectangle\&) method


Replaces the region represented by the current object with the portion of the region defined by the specified recangle that does not intersect with this region.

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | A rectangle that defines a region to complement |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) method


Replaces the region represented by the current object with the portion of the region defined by the specified path that does not intersect with this region.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | A path that defines a region to complement |

## Region::Complement(const SharedPtr\<Region\>\&) method


Replaces the region represented by the current object with the portion of the specified region that does not intersect with this region.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | A region to complement |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)