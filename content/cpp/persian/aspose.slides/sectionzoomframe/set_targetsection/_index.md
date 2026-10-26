---
title: set_TargetSection()
second_title: Aspose.Slides برای C++ مرجع API
description: آبجکت بخش را که شی Section Zoom به آن لینک می‌دهد تنظیم می‌کند. ISection را بنویسید.
type: docs
weight: 14
url: /fa/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) متد

آبجکت بخش را که شی Zoom [Section](../../section/) به آن لینک می‌دهد، تنظیم می‌کند. [ISection](../../isection/) را بنویسید.

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## توضیحات

مثال بعدی تغییر بخش هدف را نشان می‌دهد و تصویر جدیدی برای شی زوم بخش ایجاد می‌کند:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISection](../../isection/)
* کلاس [SectionZoomFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)