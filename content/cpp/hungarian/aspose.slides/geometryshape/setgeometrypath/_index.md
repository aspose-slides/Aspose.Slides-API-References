---
title: SetGeometryPath()
second_title: Aspose.Slides C++ API referencia
description: "Frissíti a forma geometriáját az IGeometryPath objektumból. A koordinátáknak a forma bal felső sarkához képest relatívnek kell lenniük. Megváltoztatja a forma típusát (ShapeType) a ShapeType::Custom értékre."
type: docs
weight: 66
url: /hu/aspose.slides/geometryshape/setgeometrypath/
---
## GeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) method

Frissíti a forma geometriáját a [IGeometryPath](../../igeometrypath/) objektumtól. A koordinátáknak a forma bal felső sarkához képest relatívnek kell lenniük. Megváltoztatja a forma típusát ([ShapeType](../../shapetype/)) [ShapeType::Custom](../../shapetype/)-ra.

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | Geometriai útvonal |
## Megjegyzések

Példa: 
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

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IGeometryPath](../../igeometrypath/)
* Osztály [GeometryShape](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)