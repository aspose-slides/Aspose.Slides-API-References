---
title: SetGeometryPaths()
second_title: Aspose.Slides para C++ Referência da API
description: "Atualiza a geometria da forma a partir de um array de IGeometryPath. As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma (ShapeType) para ShapeType::Custom."
type: docs
weight: 79
url: /pt/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) método

Atualiza a geometria da forma a partir de um array de [IGeometryPath](../../igeometrypath/). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([ShapeType](../../shapetype/)) para [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Caminhos de geometria do array |

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

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IGeometryPath](../../igeometrypath/)
* Classe [GeometryShape](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)