---
title: get_Title()
second_title: Aspose.Slides for C++ API 参考
description: 返回 Summary Zoom Section 对象的文本标题。
type: docs
weight: 1
url: /zh/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() 方法

返回 Summary Zoom [Section](../../section/) 对象的文本标题。

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
```

## 备注

示例: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## 另见

* 类 [String](../../../system/string/)
* 类 [SummaryZoomSection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)