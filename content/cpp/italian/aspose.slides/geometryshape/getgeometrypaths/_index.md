---
title: GetGeometryPaths()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce una copia del percorso della forma geometrica. Le coordinate sono relative all'angolo in alto a sinistra della forma.
type: docs
weight: 53
url: /it/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() metodo


Restituisce una copia del percorso della forma geometrica. Le coordinate sono relative all'angolo in alto a sinistra della forma.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### Valore di ritorno

Array di [IGeometryPath](../../igeometrypath/)
## Osservazioni



Esempio: 
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

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IGeometryPath](../../igeometrypath/)
* Classe [GeometryShape](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)