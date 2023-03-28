---
title: SetGeometryPaths()
second_title: Aspose.Slides for C++ API Reference
description: "Updates shape geometry from array of IGeometryPath. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType) to ShapeType::Custom."
type: docs
weight: 79
url: /cpp/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths([System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\>) method


Updates shape geometry from array of [IGeometryPath](../../igeometrypath/). Coordinates must be relative to the left top corner of the shape. Changes the type of the shape ([ShapeType](../../shapetype/)) to [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Array geometry paths |
## Remarks



Example: 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>();
auto shape = AsCast<GeometryShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 200.0f, 100.0f));

auto geometryPath = shape->GetGeometryPaths()->idx_get(0);

geometryPath->LineTo(100.0f, 50.0f, 1);
geometryPath->LineTo(100.0f, 50.0f, 4);

shape->SetGeometryPath(geometryPath);

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGeometryPath](../../igeometrypath/)
* Class [GeometryShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
