---
title: get_TargetSection()
second_title: Aspose.Slides برای مرجع API C++
description: شیء بخش را که شیء Section Zoom به آن پیوند می‌دهد، دریافت می‌کند. ISection را بخوانید.
type: docs
weight: 1
url: /fa/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() متد

شیء بخش را که شیء Zoom [Section](../../section/) به آن لینک دارد، دریافت می‌کند. [ISection](../../isection/) را بخوانید.

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## توضیحات

مثال بعدی تغییر بخش هدف را نشان می‌دهد و تصویر جدیدی برای شیء زوم بخش ایجاد می‌کند:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISection](../../isection/)
* کلاس [SectionZoomFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)