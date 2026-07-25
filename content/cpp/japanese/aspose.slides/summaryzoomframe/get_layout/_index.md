---
title: get_Layout()
second_title: Aspose.Slides for C++ API リファレンス
description: フレーム内の Summary Zoom セクションのレイアウトを取得します。既定値は GridLayout です。
type: docs
weight: 1
url: /ja/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() メソッド

フレーム内の Summary Zoom セクションのレイアウトを取得します。デフォルト値は GridLayout です。

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## 備考

この例はインデックスで Summary Zoom [Section](../../section/) 要素を取得する方法を示しています：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## 参照

* 列挙型 [ZoomLayout](../../zoomlayout/)
* クラス [SummaryZoomFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)