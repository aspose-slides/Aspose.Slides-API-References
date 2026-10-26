---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides C++ API 参考
description: 获取 Summary Zoom Frame 对象的 ISummaryZoomSectionCollection。
type: docs
weight: 14
url: /zh/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() 方法


获取 Summary Zoom Frame 对象的 [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)。

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## 备注


示例演示了通过索引获取 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* 类 [SummaryZoomFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)