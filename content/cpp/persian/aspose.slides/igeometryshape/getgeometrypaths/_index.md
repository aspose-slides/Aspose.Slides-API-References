---
title: GetGeometryPaths()
second_title: Aspose.Slides برای مرجع API C++
description: یک نسخهٔ کپی از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالای سمت چپ شکل است.
type: docs
weight: 53
url: /fa/aspose.slides/igeometryshape/getgeometrypaths/
---
## IGeometryShape::GetGeometryPaths() متد

کپی مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالای چپ شکل هستند.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::IGeometryShape::GetGeometryPaths()=0
```

### مقدار بازگشتی

آرایه‌ای از [IGeometryPath](../../igeometrypath/)
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

## مراجع مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IGeometryPath](../../igeometrypath/)
* کلاس [IGeometryShape](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)