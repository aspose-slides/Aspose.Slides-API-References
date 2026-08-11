---
title: set_TargetSection()
second_title: Aspose.Slides برای مرجع API C++
description: شیء بخش را که شی Section Zoom به آن پیوند داده شده است تنظیم می‌کند. بنویسید ISection.
type: docs
weight: 14
url: /fa/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) متد

شیء بخش را که شی [Section](../../section/) Zoom به آن پیوند داده شده است، تنظیم می‌کند. بنویسید [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## ملاحظات

این مثال تغییر بخش هدف را نشان می‌دهد و یک تصویر جدید برای شیء زوم بخش ایجاد می‌کند: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISection](../../isection/)
* کلاس [ISectionZoomFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)