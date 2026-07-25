---
title: get_Layout()
second_title: Aspose.Slides for C++ API リファレンス
description: フレーム内の Summary Zoom セクションのレイアウトを取得します。デフォルト値は GridLayout です。
type: docs
weight: 1
url: /ja/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() メソッド

フレーム内の Summary Zoom セクションのレイアウトを取得します。デフォルト値は GridLayout です。

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## 備考

この例はインデックスで Summary Zoom [Section](../../section/) 要素を取得することを示します: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## 参照

* 列挙体 [ZoomLayout](../../zoomlayout/)
* クラス [ISummaryZoomFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)