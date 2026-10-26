---
title: SetGeometryPaths()
second_title: Referencia de API de Aspose.Slides para C++
description: "Actualiza la geometría de la forma a partir de una matriz de IGeometryPath. Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma (ShapeType) a ShapeType::Custom."
type: docs
weight: 79
url: /es/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) método


Actualiza la geometría de la forma a partir de una matriz de [IGeometryPath](../../igeometrypath/). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([ShapeType](../../shapetype/)) a [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Matriz de rutas de geometría |
## Observaciones



Ejemplo: 
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

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IGeometryPath](../../igeometrypath/)
* Clase [GeometryShape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)