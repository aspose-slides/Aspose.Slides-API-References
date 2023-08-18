---
title: Xor()
second_title: Aspose.Slides for C++ API Reference
description: Replaces the region represented by the current object with the portions of this region and the region defined by the specified recangle that do not intersect.
type: docs
weight: 144
url: /system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) method


Replaces the region represented by the current object with the portions of this region and the region defined by the specified recangle that do not intersect.

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | A rectangle that defines a region to xor with the region represented by the current object |

## Region::Xor(const Rectangle\&) method


Replaces the region represented by the current object with the portions of this region and the region defined by the specified recangle that do not intersect.

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | A rectangle that defines a region to xor with the region represented by the current object |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) method


Replaces the region represented by the current object with the portions of this region and the region defined by the specified path that do not intersect.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | A path that defines a region to xor with the region represented by the current object |

## Region::Xor(const SharedPtr\<Region\>\&) method


Replaces the region represented by the current object with the portions of this region and the specified region that do not intersect.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | A region to xor with the region represented by the current object |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)