---
title: get_Layout()
second_title: Aspose.Slides for C++ API 參考
description: 取得框架中 Summary Zoom 區段的佈局。預設值為 GridLayout。
type: docs
weight: 1
url: /zh-hant/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() 方法


取得框架中 Summary Zoom 部分的佈局。預設值為 GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## 備註


此範例示範透過索引取得 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## 另請參閱

* 列舉 [ZoomLayout](../../zoomlayout/)
* 類別 [ISummaryZoomFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)