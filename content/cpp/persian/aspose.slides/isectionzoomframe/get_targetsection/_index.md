---
title: get_TargetSection()
second_title: Aspose.Slides برای مرجع API C++
description: شیء بخش را که شیء Section Zoom به آن پیوند دارد، دریافت می‌کند. ISection را بخوانید.
type: docs
weight: 1
url: /fa/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() method

شیء بخش را که شیء [Section](../../section/) Zoom به آن پیوند دارد، دریافت می‌کند. ببینید [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## ملاحظات

این مثال تغییر بخش هدف را نشان می‌دهد و تصویر جدیدی برای شیء section zoom ایجاد می‌کند: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISection](../../isection/)
* کلاس [ISectionZoomFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)