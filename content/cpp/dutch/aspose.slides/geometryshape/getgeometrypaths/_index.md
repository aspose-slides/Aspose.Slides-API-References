---
title: GetGeometryPaths()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een kopie van het pad van de geometrische vorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm.
type: docs
weight: 53
url: /nl/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() methode


Retourneert een kopie van het pad van de geometrische vorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### Retourwaarde

Array of [IGeometryPath](../../igeometrypath/)
## Opmerkingen



Voorbeeld: 
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

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IGeometryPath](../../igeometrypath/)
* Klasse [GeometryShape](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)