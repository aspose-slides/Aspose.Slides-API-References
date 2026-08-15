---
title: set_TargetSection()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定 Section Zoom 物件所連結的區段物件。寫入 ISection.
type: docs
weight: 14
url: /zh-hant/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) 方法

設定 [Section](../../section/) Zoom 物件所連結的區段物件。寫入 [ISection](../../isection/)。

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## 備註

以下範例示範變更目標區段，並為 section zoom 物件建立新影像：
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISection](../../isection/)
* 類別 [SectionZoomFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)