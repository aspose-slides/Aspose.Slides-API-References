---
title: SetGeometryPath()
second_title: Aspose.Slides para C++ Referência da API
description: "Atualiza a geometria da forma a partir do objeto IGeometryPath. As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma (ShapeType) para ShapeType::Custom."
type: docs
weight: 66
url: /pt/aspose.slides/geometryshape/setgeometrypath/
---
## GeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) método

Atualiza a geometria da forma a partir do objeto [IGeometryPath](../../igeometrypath/). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([ShapeType](../../shapetype/)) para [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | Caminho da geometria |
## Observações



Exemplo: 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>();

auto shape = AsCast<GeometryShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 200.0f, 100.0f));

auto geometryPath0 = MakeObject<GeometryPath>();
geometryPath0->MoveTo(0.0f, 0.0f);
geometryPath0->LineTo(shape->get_Width(), 0.0f);
geometryPath0->LineTo(shape->get_Width(), shape->get_Height() / 3);
geometryPath0->LineTo(0.0f, shape->get_Height() / 3);
geometryPath0->CloseFigure();

auto geometryPath1 = MakeObject<GeometryPath>();
geometryPath1->MoveTo(0.0f, shape->get_Height() / 3 * 2);
geometryPath1->LineTo(shape->get_Width(), shape->get_Height() / 3 * 2);
geometryPath1->LineTo(shape->get_Width(), shape->get_Height());
geometryPath1->LineTo(0.0f, shape->get_Height());
geometryPath1->CloseFigure();

shape->SetGeometryPaths(StaticCastArray<SharedPtr<IGeometryPath>>(MakeArray<SharedPtr<GeometryPath>>({geometryPath0, geometryPath1})));

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGeometryPath](../../igeometrypath/)
* Class [GeometryShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)