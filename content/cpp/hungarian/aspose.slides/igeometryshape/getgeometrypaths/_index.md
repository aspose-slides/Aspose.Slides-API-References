---
title: GetGeometryPaths()
second_title: Aspose.Slides for C++ API referencia
description: Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához relatívak.
type: docs
weight: 53
url: /hu/aspose.slides/igeometryshape/getgeometrypaths/
---
## IGeometryShape::GetGeometryPaths() módszer

Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához képest relatívak.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::IGeometryShape::GetGeometryPaths()=0
```

### Visszatérési érték

Array of [IGeometryPath](../../igeometrypath/)
## Megjegyzések

Példa: 
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

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IGeometryPath](../../igeometrypath/)
* Osztály [IGeometryShape](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)