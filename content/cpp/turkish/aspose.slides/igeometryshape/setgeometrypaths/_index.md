---
title: SetGeometryPaths()
second_title: Aspose.Slides için C++ API Referansı
description: "Şeklin geometrisini IGeometryPath dizisinden günceller. Koordinatlar, şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini (ShapeType) ShapeType::Custom olarak değiştirir."
type: docs
weight: 79
url: /tr/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) method

Şeklin geometriğini [IGeometryPath](../../igeometrypath/) dizisinden günceller. Koordinatlar, şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini ([ShapeType](../../shapetype/)) [ShapeType::Custom](../../shapetype/) olarak değiştirir.

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Geometri yolları dizisi |

## Açıklamalar

Örnek:
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

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGeometryPath](../../igeometrypath/)
* Class [IGeometryShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)