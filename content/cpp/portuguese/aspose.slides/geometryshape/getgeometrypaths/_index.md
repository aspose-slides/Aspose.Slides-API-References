---
title: GetGeometryPaths()
second_title: Referência da API do Aspose.Slides para C++
description: Retorna uma cópia do caminho da forma geométrica. As coordenadas são relativas ao canto superior esquerdo da forma.
type: docs
weight: 53
url: /pt/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() método

Retorna uma cópia do caminho da forma geométrica. As coordenadas são relativas ao canto superior esquerdo da forma.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```

### Valor de retorno

Matriz de [IGeometryPath](../../igeometrypath/)
## Observações



Exemplo: 
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

## Veja também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IGeometryPath](../../igeometrypath/)
* Classe [GeometryShape](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)