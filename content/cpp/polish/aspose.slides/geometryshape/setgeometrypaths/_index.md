---
title: SetGeometryPaths()
second_title: Aspose.Slides dla C++ – referencja API
description: "Aktualizuje geometrię kształtu z tablicy IGeometryPath. Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu (ShapeType) na ShapeType::Custom."
type: docs
weight: 79
url: /pl/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) metoda


Aktualizuje geometrię kształtu z tablicy [IGeometryPath](../../igeometrypath/). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu ([ShapeType](../../shapetype/)) na [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Tablica ścieżek geometrycznych |
## Uwagi



Przykład: 
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

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGeometryPath](../../igeometrypath/)
* Class [GeometryShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)