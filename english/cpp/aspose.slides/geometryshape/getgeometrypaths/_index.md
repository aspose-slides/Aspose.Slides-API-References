---
title: GetGeometryPaths()
second_title: Aspose.Slides for C++ API Reference
description: Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape.
type: docs
weight: 53
url: /cpp/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() method


Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### Return Value

Array of [IGeometryPath](../../igeometrypath/)
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