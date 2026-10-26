---
title: SetGeometryPaths()
second_title: Aspose.Slides för C++ API-referens
description: "Uppdaterar formens geometri från en array av IGeometryPath. Koordinaterna måste vara relativa till formens övre vänstra hörn. Ändrar formens typ (ShapeType) till ShapeType::Custom."
type: docs
weight: 79
url: /sv/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) metod


Uppdaterar formens geometri från en array av [IGeometryPath](../../igeometrypath/). Koordinaterna måste vara relativa till formens övre vänstra hörn. Ändrar formens typ ([ShapeType](../../shapetype/)) till [ShapeType::Custom](../../shapetype/).

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Array med geometrivägar |
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

## Se också

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IGeometryPath](../../igeometrypath/)
* Klass [IGeometryShape](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)