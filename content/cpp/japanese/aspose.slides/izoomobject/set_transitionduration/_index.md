---
title: set_TransitionDuration()
second_title: Aspose.Slides for C++ API リファレンス
description: "Zoom とスライド間のトランジションの期間を設定します。float を記述します。デフォルト値: 1.0f"
type: docs
weight: 118
url: /ja/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) メソッド


Sets the duration of the transition between Zoom and slide. Write **float**. Default value: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## 備考


If not specified (TransitionDur = 0), it will use the destination slide transition and the timings associated with that transition. 

the example demonstrates changing the duration of the transition between Zoom and slide: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## 参照

* クラス [IZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)