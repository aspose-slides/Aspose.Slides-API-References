---
title: SetGeometryPaths()
second_title: Aspose.Slides für C++ API-Referenz
description: "Aktualisiert die Geometrie der Form aus einem Array von IGeometryPath. Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form (ShapeType) zu ShapeType::Custom."
type: docs
weight: 79
url: /de/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) Methode

Aktualisiert die Geometrie der Form aus einem Array von [IGeometryPath](../../igeometrypath/). Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ([ShapeType](../../shapetype/)) zu [ShapeType::Custom](../../shapetype/).

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Array-Geometriepfade |

## Hinweise



Beispiel: 
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

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGeometryPath](../../igeometrypath/)
* Class [IGeometryShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)