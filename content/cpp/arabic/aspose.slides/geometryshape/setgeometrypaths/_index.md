---
title: SetGeometryPaths()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يقوم بتحديث هندسة الشكل من مصفوفة من IGeometryPath. يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل (ShapeType) إلى ShapeType::Custom."
type: docs
weight: 79
url: /ar/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) طريقة

يقوم بتحديث هندسة الشكل من مصفوفة من [IGeometryPath](../../igeometrypath/). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([ShapeType](../../shapetype/)) إلى [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | مسارات هندسة المصفوفة |
## ملاحظات

مثال:
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

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IGeometryPath](../../igeometrypath/)
* فئة [GeometryShape](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)