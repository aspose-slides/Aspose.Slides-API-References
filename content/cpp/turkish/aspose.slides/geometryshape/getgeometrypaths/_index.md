---
title: GetGeometryPaths()
second_title: Aspose.Slides için C++ API Referansı
description: Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar, şeklin sol üst köşesine görecelidir.
type: docs
weight: 53
url: /tr/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() metot

Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar, şeklin sol üst köşesine göre görecelidir.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```

### Dönüş Değeri

Dizi [IGeometryPath](../../igeometrypath/)

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
* Sınıf [IGeometryPath](../../igeometrypath/)
* Sınıf [GeometryShape](../)
* AdAlanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)