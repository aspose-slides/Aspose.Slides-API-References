---
title: SetGeometryPath()
second_title: Aspose.Slides for C++ API Reference
description: "Updates shape geometry from IGeometryPath object. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType) to ShapeType::Custom."
type: docs
weight: 66
url: /aspose.slides/geometryshape/setgeometrypath/
---
## GeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) method


Updates shape geometry from [IGeometryPath](../../igeometrypath/) object. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape ([ShapeType](../../shapetype/)) to [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | Geometry path |
## Remarks



Example: 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>();

auto shape = AsCast<GeometryShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 200.0f, 100.0f));

auto geometryPath0 = MakeObject<GeometryPath>();
geometryPath0->MoveTo(0.0f, 0.0f);
geometryPath0->LineTo(shape->get_Width(), 0.0f);
geometryPath0->LineTo(shape->get_Width(), shape->get_Height() / 3);
geometryPath0->LineTo(0.0f, shape->get_Height() / 3);
geometryPath0->CloseFigure();

auto geometryPath1 = MakeObject<GeometryPath>();
geometryPath1->MoveTo(0.0f, shape->get_Height() / 3 * 2);
geometryPath1->LineTo(shape->get_Width(), shape->get_Height() / 3 * 2);
geometryPath1->LineTo(shape->get_Width(), shape->get_Height());
geometryPath1->LineTo(0.0f, shape->get_Height());
geometryPath1->CloseFigure();

shape->SetGeometryPaths(StaticCastArray<SharedPtr<IGeometryPath>>(MakeArray<SharedPtr<GeometryPath>>({geometryPath0, geometryPath1})));

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGeometryPath](../../igeometrypath/)
* Class [GeometryShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)