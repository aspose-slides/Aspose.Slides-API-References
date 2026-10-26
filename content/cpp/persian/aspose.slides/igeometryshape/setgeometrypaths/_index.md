---
title: SetGeometryPaths()
second_title: مرجع API Aspose.Slides برای C++
description: "هندسهٔ شکل را با استفاده از آرایه‌ای از IGeometryPath به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالایی چپ شکل نسبت‌داده شوند. نوع شکل (ShapeType) به ShapeType::Custom تغییر می‌کند."
type: docs
weight: 79
url: /fa/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) متد

هندسهٔ شکل را با استفاده از آرایه‌ای از [IGeometryPath](../../igeometrypath/) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالایی چپ شکل نسبت‌داده شوند. نوع شکل ([ShapeType](../../shapetype/)) به [ShapeType::Custom](../../shapetype/) تغییر می‌کند.

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | آرایه مسیرهای هندسی |
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

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IGeometryPath](../../igeometrypath/)
* کلاس [IGeometryShape](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)