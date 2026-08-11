---
title: SetGeometryPaths()
second_title: مرجع API Aspose.Slides برای C++
description: "به‌روز رسانی هندسه شکل از آرایه‌ای از IGeometryPath. مختصات باید نسبی به گوشهٔ بالایی سمت چپ شکل باشد. نوع شکل (ShapeType) را به ShapeType::Custom تغییر می‌دهد."
type: docs
weight: 79
url: /fa/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) متد

به‌روز رسانی هندسه شکل از آرایه‌ای از [IGeometryPath](../../igeometrypath/). مختصات باید نسبی به گوشهٔ بالایی سمت چپ شکل باشد. نوع شکل ([ShapeType](../../shapetype/)) را به [ShapeType::Custom](../../shapetype/) تغییر می‌دهد.

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | آرایهٔ مسیرهای هندسی |
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

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IGeometryPath](../../igeometrypath/)
* کلاس [GeometryShape](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)