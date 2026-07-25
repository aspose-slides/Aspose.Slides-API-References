---
title: set_TargetSlide()
second_title: Aspose.Slides for C++ API リファレンス
description: Slide Zoom オブジェクトがリンクするスライドオブジェクトを設定します。ISlide に書き込みます。
type: docs
weight: 14
url: /ja/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) メソッド


[Slide](../../slide/) Zoom オブジェクトがリンクするスライドオブジェクトを設定します。[ISlide](../../islide/) を書き込みます。

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## 備考


次の例は、対象スライドの変更を示し、[Slide](../../slide/) Zoom オブジェクトの新しい画像を作成します: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISlide](../../islide/)
* クラス [ZoomFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)