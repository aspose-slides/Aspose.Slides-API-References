---
title: SetGeometryPaths()
second_title: Aspose.Slides voor C++ API-referentie
description: "Werkt de vormgeometrie bij vanuit een array van IGeometryPath. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Wijzigt het type van de vorm (ShapeType) naar ShapeType::Custom."
type: docs
weight: 79
url: /nl/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) methode

Updates shape geometry from array of [IGeometryPath](../../igeometrypath/). Coordinates must be relative to the left top corner of the shape. Changes the type of the shape ([ShapeType](../../shapetype/)) to [ShapeType::Custom](../../shapetype/).

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Array geometry paths |

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
* Klasse [IGeometryShape](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)