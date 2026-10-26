---
title: SetGeometryPaths()
second_title: Aspose.Slides per C++ API Reference
description: "Aggiorna la geometria della forma da un array di IGeometryPath. Le coordinate devono essere relative all'angolo in alto a sinistra della forma. Cambia il tipo della forma (ShapeType) in ShapeType::Custom."
type: docs
weight: 79
url: /it/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) method


Aggiorna la geometria della forma da un array di [IGeometryPath](../../igeometrypath/). Le coordinate devono essere relative all'angolo in alto a sinistra della forma. Cambia il tipo della forma ([ShapeType](../../shapetype/)) in [ShapeType::Custom](../../shapetype/).

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Array di percorsi di geometria |
## Remarks



Example: 
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

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IGeometryPath](../../igeometrypath/)
* Classe [IGeometryShape](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)