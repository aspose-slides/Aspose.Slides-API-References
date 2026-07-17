---
title: set_Title()
second_title: Aspose.Slides C++ API 参考
description: 返回 Summary Zoom Section 对象的文本标题。
type: docs
weight: 14
url: /zh/aspose.slides/isummaryzoomsection/set_title/
---
## ISummaryZoomSection::set_Title(System::String) 方法

Returns the text title of the Summary Zoom [Section](../../section/) object.

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Title(System::String value)=0
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
* 类 [ISummaryZoomSection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)