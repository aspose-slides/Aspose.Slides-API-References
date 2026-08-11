---
title: GetGeometryPaths()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل.
type: docs
weight: 53
url: /ar/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() طريقة


يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### قيمة الإرجاع

مصفوفة من [IGeometryPath](../../igeometrypath/)
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

## انظر أيضاً

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IGeometryPath](../../igeometrypath/)
* فئة [GeometryShape](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)