---
title: get_Layout()
second_title: Aspose.Slides C++ API 参考
description: 获取帧中 Summary Zoom 部分的布局。默认值为 GridLayout。
type: docs
weight: 1
url: /zh/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() 方法


获取帧中 Summary Zoom 部分的布局。默认值为 GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## 备注


示例演示了通过索引获取 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## 另见

* 枚举 [ZoomLayout](../../zoomlayout/)
* 类 [SummaryZoomFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)