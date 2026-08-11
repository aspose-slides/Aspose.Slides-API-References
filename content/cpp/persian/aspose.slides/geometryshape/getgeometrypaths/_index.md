---
title: GetGeometryPaths()
second_title: Aspose.Slides برای C++ مرجع API
description: یک کپی از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالا سمت چپ شکل هستند.
type: docs
weight: 53
url: /fa/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() متد


یک کپی از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشه بالا-چپ شکل هستند.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### مقدار برگشتی

آرایه‌ای از [IGeometryPath](../../igeometrypath/)
## توضیحات



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

## مراجعه

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IGeometryPath](../../igeometrypath/)
* کلاس [GeometryShape](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)