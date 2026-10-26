---
title: set_Description()
second_title: Aspose.Slides C++ API 參考文件
description: 傳回 Summary Zoom Section 物件的文字描述。
type: docs
weight: 40
url: /zh-hant/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) 方法

返回 Summary Zoom [Section](../../section/) 物件的文字描述。

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
```

## 備註

範例：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [SummaryZoomSection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)