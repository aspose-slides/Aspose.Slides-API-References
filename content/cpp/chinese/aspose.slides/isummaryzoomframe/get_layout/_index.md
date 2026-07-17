---
title: get_Layout()
second_title: Aspose.Slides for C++ API 参考
description: 获取帧中摘要缩放部分的布局。默认值为 GridLayout。
type: docs
weight: 1
url: /zh/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() 方法


获取帧中摘要缩放部分的布局。默认值为 GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## 备注


示例演示如何通过索引获取摘要缩放 [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## 另请参阅

* 枚举 [ZoomLayout](../../zoomlayout/)
* 类 [ISummaryZoomFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)