---
title: get_TargetSection()
second_title: Aspose.Slides for C++ API 參考
description: 取得與 Section Zoom 物件連結的節物件。閱讀 ISection。
type: docs
weight: 1
url: /zh-hant/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() 方法


取得與 [Section](../../section/) Zoom 物件連結的節物件。閱讀 [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## 備註


此範例示範變更目標節並為節縮放物件建立新影像： 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## 另見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISection](../../isection/)
* 類別 [ISectionZoomFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)