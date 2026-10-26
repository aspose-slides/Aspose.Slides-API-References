---
title: GetGeometryPaths()
second_title: Aspose.Slides dla C++ – referencja API
description: Zwraca kopię ścieżki kształtu geometrycznego. Współrzędne są względem lewego górnego rogu kształtu.
type: docs
weight: 53
url: /pl/aspose.slides/igeometryshape/getgeometrypaths/
---
## IGeometryShape::GetGeometryPaths() method


Zwraca kopię ścieżki kształtu geometrycznego. Współrzędne są względem lewego górnego rogu kształtu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::IGeometryShape::GetGeometryPaths()=0
```


### Wartość zwracana

Array of [IGeometryPath](../../igeometrypath/)
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

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IGeometryPath](../../igeometrypath/)
* Klasa [IGeometryShape](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)