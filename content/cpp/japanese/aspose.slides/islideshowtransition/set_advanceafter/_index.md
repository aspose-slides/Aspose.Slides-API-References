---
title: set_AdvanceAfter()
second_title: Aspose.Slides for C++ API リファレンス
description: この属性は、スライドショーが一定時間後に次のスライドへ移動するかどうかを指定します。bool を書き込みます。
type: docs
weight: 118
url: /ja/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) メソッド

この属性は、スライドショーが一定時間後に次のスライドへ移動するかどうかを指定します。**bool** を書き込みます。

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 最初のスライド遷移を取得
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Advance Slide After フラグがチェックされているか確認
if (slideTransition->get_AdvanceAfter())
{
    // Advance Slide After 時間の値を取得
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 参照

* クラス [ISlideShowTransition](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)