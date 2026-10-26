---
title: GetGeometryPaths()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához relatívak.
type: docs
weight: 53
url: /hu/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() metódus


Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához relatívak.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### Visszatérési érték

A [IGeometryPath](../../igeometrypath/) tömb

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
* Osztály [GeometryShape](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)