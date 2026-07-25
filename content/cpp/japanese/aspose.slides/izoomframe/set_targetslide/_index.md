---
title: set_TargetSlide()
second_title: Aspose.Slides for C++ API リファレンス
description: Slide Zoom オブジェクトがリンクするスライド オブジェクトを設定します。ISlide を書き込みます。
type: docs
weight: 14
url: /ja/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) メソッド


[Slide](../../slide/) Zoom オブジェクトがリンクするスライド オブジェクトを設定します。[ISlide](../../islide/) を書き込みます。

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## 備考


次の例は、ターゲット スライドの変更を示し、[Slide](../../slide/) Zoom オブジェクトの新しい画像を作成します: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [IZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)