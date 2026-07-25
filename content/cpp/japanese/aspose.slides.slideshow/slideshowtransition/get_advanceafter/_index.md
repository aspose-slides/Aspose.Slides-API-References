---
title: get_AdvanceAfter()
second_title: Aspose.Slides for C++ API リファレンス
description: この属性は、スライドショーが一定時間後に次のスライドへ移動するかどうかを指定します。bool を読み取ります。
type: docs
weight: 105
url: /ja/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() メソッド

この属性は、スライドショーが一定時間後に次のスライドへ移動するかどうかを指定します。**bool** を読み取ります。

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 最初のスライド Transition を取得
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Advance Slide After フラグがチェックされているか確認
if (slideTransition->get_AdvanceAfter())
{
    // Advance Slide After Time 値を取得
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 参照

* クラス [SlideShowTransition](../)
* 名前空間 [Aspose::Slides::SlideShow](../../)
* ライブラリ [Aspose.Slides](../../../)