---
title: get_TransitionDuration()
second_title: Aspose.Slides for C++ API リファレンス
description: "Zoom とスライド間の遷移の期間を取得します。float を読み取ります。デフォルト値: 1.0f"
type: docs
weight: 105
url: /ja/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() メソッド

Zoom とスライド間の遷移の期間を取得します。**float** を読み取ります。デフォルト値: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## 備考

指定されていない場合 (TransitionDur = 0)、対象スライドの遷移とその遷移に関連付けられたタイミングが使用されます。

例では、Zoom とスライド間の遷移の期間を変更する方法を示しています:
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