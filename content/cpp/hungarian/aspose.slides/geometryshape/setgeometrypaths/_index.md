---
title: SetGeometryPaths()
second_title: Aspose.Slides a C++ API hivatkozás
description: "Frissíti az alakzat geometriáját az IGeometryPath tömbből. A koordinátáknak az alakzat bal felső sarkához kell viszonyulniuk. Az alakzat típusát (ShapeType) a ShapeType::Custom-ra változtatja."
type: docs
weight: 79
url: /hu/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) metódus

Frissíti az alakzat geometriáját a [IGeometryPath](../../igeometrypath/) tömbből. A koordinátáknak az alakzat bal felső sarkához képest relatívnek kell lenniük. Az alakzat típusát ([ShapeType](../../shapetype/)) [ShapeType::Custom](../../shapetype/) típusra változtatja.

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Geometriai útvonalak tömbje |

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

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IGeometryPath](../../igeometrypath/)
* Osztály [GeometryShape](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)