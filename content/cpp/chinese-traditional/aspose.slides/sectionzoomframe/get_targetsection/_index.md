---
title: get_TargetSection()
second_title: Aspose.Slides for C++ API 參考
description: 取得 Section Zoom 物件所連結的章節物件。請閱讀 ISection.
type: docs
weight: 1
url: /zh-hant/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() 方法


取得 [Section](../../section/) Zoom 物件所連結的章節物件。請閱讀 [ISection](../../isection/)。

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## 備註


以下範例示範變更目標章節並為 section zoom 物件建立新的影像：
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISection](../../isection/)
* 類別 [SectionZoomFrame](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)