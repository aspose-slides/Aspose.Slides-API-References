---
title: GetGeometryPaths()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt eine Kopie des Pfads der geometrischen Form zurück. Die Koordinaten sind relativ zur linken oberen Ecke der Form.
type: docs
weight: 53
url: /de/aspose.slides/igeometryshape/getgeometrypaths/
---
## IGeometryShape::GetGeometryPaths() Methode


Gibt eine Kopie des Pfads der geometrischen Form zurück. Die Koordinaten sind relativ zur linken oberen Ecke der Form.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::IGeometryShape::GetGeometryPaths()=0
```


### Rückgabewert

Array von [IGeometryPath](../../igeometrypath/)
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
* Klasse [IGeometryPath](../../igeometrypath/)
* Klasse [IGeometryShape](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)