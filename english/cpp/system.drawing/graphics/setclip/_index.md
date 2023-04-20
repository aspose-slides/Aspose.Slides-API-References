---
title: SetClip()
second_title: Aspose.Slides for C++ API Reference
description: Sets the clipping region of drawing surface represented by the current Graphics object to the result of the specified operation that combines the current clip region and the specified region.
type: docs
weight: 690
url: /cpp/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) method


Sets the clipping region of drawing surface represented by the current [Graphics](../) object to the result of the specified operation that combines the current clip region and the specified region.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) method


Sets the clipping region of drawing surface represented by the current [Graphics](../) object to the result of the specified operation that combines the current clip region and the specified region.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) method


Sets the clipping region of drawing surface represented by the current [Graphics](../) object to the result of the specified operation that combines the current clip region and the specified region.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) method


NOT IMPLEMENTED.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) method


Sets the clipping region of drawing surface represented by the current [Graphics](../) object to the result of the specified operation that combines the current clip region and the region specified by a graphics path.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## See Also

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)