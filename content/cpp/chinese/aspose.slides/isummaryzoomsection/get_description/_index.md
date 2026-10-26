---
title: get_Description()
second_title: Aspose.Slides C++ API 参考
description: 返回 Summary Zoom Section 对象的文本描述。
type: docs
weight: 27
url: /zh/aspose.slides/isummaryzoomsection/get_description/
---
## ISummaryZoomSection::get_Description() 方法


返回 Summary Zoom [Section](../../section/) 对象的文本描述。

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Description()=0
```

## 备注


示例: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## 另见

* 类 [String](../../../system/string/)
* 类 [ISummaryZoomSection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)