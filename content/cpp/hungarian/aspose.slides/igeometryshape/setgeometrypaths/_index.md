---
title: SetGeometryPaths()
second_title: Aspose.Slides C++ API referenciája
description: "Frissíti a forma geometriáját az IGeometryPath tömbből. A koordinátáknak a forma bal felső sarkához képest relatívnak kell lenniük. Megváltoztatja a forma típusát (ShapeType) a ShapeType::Custom-ra."
type: docs
weight: 79
url: /hu/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) metódus


Frissíti a forma geometriáját a [IGeometryPath](../../igeometrypath/) tömbből. A koordinátáknak a forma bal felső sarkához képest relatívnak kell lenniük. Megváltoztatja a forma típusát ([ShapeType](../../shapetype/)) [ShapeType::Custom](../../shapetype/)-ra.

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Tömb geometriai útvonalak |
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