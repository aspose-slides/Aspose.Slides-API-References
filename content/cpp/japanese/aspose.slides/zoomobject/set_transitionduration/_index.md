---
title: set_TransitionDuration()
second_title: Aspose.Slides for C++ API リファレンス
description: "Zoom とスライド間の遷移時間を設定します。float で指定します。デフォルト値: 1.0f"
type: docs
weight: 118
url: /ja/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) メソッド


Zoom とスライド間の遷移時間を設定します。**float** で指定します。デフォルト値: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## 備考


指定されない場合 (TransitionDur = 0)、目的地のスライド遷移とその遷移に関連付けられたタイミングが使用されます。

この例は、Zoom とスライド間の遷移時間を変更する方法を示しています: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## 参照

* クラス [ZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)