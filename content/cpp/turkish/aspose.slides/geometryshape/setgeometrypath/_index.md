---
title: SetGeometryPath()
second_title: Aspose.Slides için C++ API Referansı
description: "IGeometryPath nesnesinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göreceli olmalıdır. Şeklin tipini (ShapeType) ShapeType::Custom olarak değiştirir."
type: docs
weight: 66
url: /tr/aspose.slides/geometryshape/setgeometrypath/
---
## GeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) metot


Şekil geometriğini [IGeometryPath](../../igeometrypath/) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini ([ShapeType](../../shapetype/)) [ShapeType::Custom](../../shapetype/) olarak değiştirir.

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath) override
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | Geometri yolu |
## Açıklamalar



Örnek: 
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

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IGeometryPath](../../igeometrypath/)
* Sınıf [GeometryShape](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)