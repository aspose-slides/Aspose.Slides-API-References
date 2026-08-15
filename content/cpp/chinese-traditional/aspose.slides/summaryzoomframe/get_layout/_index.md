---
title: get_Layout()
second_title: Aspose.Slides C++ API 參考
description: 取得框架中 Summary Zoom Sections 的佈局。預設值為 GridLayout。
type: docs
weight: 1
url: /zh-hant/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() 方法


取得框架中 Summary Zoom Sections 的佈局。預設值為 GridLayout。

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
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
* 類別 [SummaryZoomFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)