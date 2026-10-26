---
title: SetGeometryPaths()
second_title: Aspose.Slides för C++ API-referens
description: "Uppdaterar figurens geometri från en array av IGeometryPath. Koordinater måste vara relativa till figurens vänstra övre hörn. Ändrar figurens typ (ShapeType) till ShapeType::Custom."
type: docs
weight: 79
url: /sv/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) metod

Uppdaterar formens geometri från en matris av [IGeometryPath](../../igeometrypath/). Koordinater måste vara relativa till formens vänstra övre hörn. Ändrar formens typ ([ShapeType](../../shapetype/)) till [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Array av geometriska banor |
## Anmärkningar



Exempel: 
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

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IGeometryPath](../../igeometrypath/)
* Klass [GeometryShape](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)