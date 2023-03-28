---
title: GraphicsPath()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of GraphicsPath class with the specified fill mode.
type: docs
weight: 1
url: /cpp/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath([FillMode](../../fillmode/)) constructor


Constructs a new instance of [GraphicsPath](../) class with the specified fill mode.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Specifies how the interior of the closed path represented by the object being created should be filled |

## See Also

* Enum [FillMode](../../fillmode/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
## GraphicsPath::GraphicsPath(const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\&, const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../../fillmode/)) constructor


Constructs a new instance of [GraphicsPath](../) object that represents the specified path.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | An array containing the points that specify the path to be represented by the object being created |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | An array containing the values tha specify the types of the corresponding points in **pts** array |
| fillMode | [FillMode](../../fillmode/) | Specifies how the interior of the closed path represented by the object being created should be filled |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../system.drawing/point/)
* Enum [FillMode](../../fillmode/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
## GraphicsPath::GraphicsPath(const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../../fillmode/)) constructor


Constructs a new instance of [GraphicsPath](../) object that represents the specified path.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | An array containing the points that specify the path to be represented by the object being created |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | An array containing the values tha specify the types of the corresponding points in **pts** array |
| fillMode | [FillMode](../../fillmode/) | Specifies how the interior of the closed path represented by the object being created should be filled |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Enum [FillMode](../../fillmode/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
## GraphicsPath::GraphicsPath(const SkPath\&) constructor




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## See Also

* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
