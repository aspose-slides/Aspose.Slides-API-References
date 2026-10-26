---
title: SetGeometryPaths()
second_title: Riferimento API Aspose.Slides per C++
description: "Aggiorna la geometria della forma da un array di IGeometryPath. Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma (ShapeType) in ShapeType::Custom."
type: docs
weight: 79
url: /it/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) metodo

Aggiorna la geometria della forma da un array di [IGeometryPath](../../igeometrypath/). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([ShapeType](../../shapetype/)) in [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Array di percorsi geometrici |

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
* Libreria [Aspose.Slides](../../../)