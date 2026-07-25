---
title: get_TargetSlide()
second_title: Aspose.Slides for C++ API リファレンス
description: Slide Zoom オブジェクトがリンクするスライド オブジェクトを取得します。ISlide を参照してください。
type: docs
weight: 1
url: /ja/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() メソッド

[Slide](../../slide/) Zoom オブジェクトがリンクするスライド オブジェクトを取得します。[ISlide](../../islide/) を参照してください。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## 備考

次の例は、対象スライドを変更し、[Slide](../../slide/) Zoom オブジェクトの新しい画像を作成する方法を示します:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISlide](../../islide/)
* クラス [IZoomFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)