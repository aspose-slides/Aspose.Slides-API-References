---
title: SetGeometryPaths()
second_title: Aspose.Slides için C++ API Referansı
description: "Şeklin geometrisini IGeometryPath dizisinden günceller. Koordinatlar, şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini (ShapeType) ShapeType::Custom olarak değiştirir."
type: docs
weight: 79
url: /tr/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) metodu

Şekil geometrisini [IGeometryPath](../../igeometrypath/) dizisinden günceller. Koordinatlar, şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini ([ShapeType](../../shapetype/)) [ShapeType::Custom](../../shapetype/) olarak değiştirir.

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Dizi geometri yolları |

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

## İlgili

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IGeometryPath](../../igeometrypath/)
* Sınıf [GeometryShape](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)