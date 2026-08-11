---
title: SetGeometryPath()
second_title: مرجع برنامه‌نویسی Aspose.Slides برای C++
description: "هندسهٔ شکل را از شیء IGeometryPath به‌روزرسانی می‌کند. مختصات باید نسبی به گوشهٔ بالا-چپ شکل باشد. نوع شکل (ShapeType) را به ShapeType::Custom تغییر می‌دهد."
type: docs
weight: 66
url: /fa/aspose.slides/igeometryshape/setgeometrypath/
---
## IGeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) متد

شکل هندسی را از شیء [IGeometryPath](../../igeometrypath/) به‌روزرسانی می‌کند. مختصات باید نسبی به گوشهٔ بالا-چپ شکل باشد. نوع شکل ([ShapeType](../../shapetype/)) به [ShapeType::Custom](../../shapetype/) تغییر می‌یابد.

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | مسیر هندسی |
## نکات



مثال: 
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

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IGeometryPath](../../igeometrypath/)
* کلاس [IGeometryShape](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)