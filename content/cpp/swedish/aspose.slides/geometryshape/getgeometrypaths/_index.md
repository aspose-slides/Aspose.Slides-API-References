---
title: GetGeometryPaths()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en kopia av geometriformens bana. Koordinaterna är relativa till formens vänstra övre hörn.
type: docs
weight: 53
url: /sv/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() metod


Returnerar en kopia av geometriformens bana. Koordinaterna är relativt till formens vänstra övre hörn.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### Returvärde

Array av [IGeometryPath](../../igeometrypath/)
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