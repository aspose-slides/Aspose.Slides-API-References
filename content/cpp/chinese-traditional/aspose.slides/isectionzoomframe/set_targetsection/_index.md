---
title: set_TargetSection()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定與 Section Zoom 物件連結的節物件。寫入 ISection.
type: docs
weight: 14
url: /zh-hant/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) 方法


設定與 [Section](../../section/) Zoom 物件連結的節物件。寫入 [ISection](../../isection/)。

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## 備註


此範例示範變更目標節並為 section zoom 物件建立新的影像： 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISection](../../isection/)
* 類別 [ISectionZoomFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)