---
title: set_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides for C++ API リファレンス
description: 左上から右下への取り消し線（デフォルトは false）。ボーダーボックスの左上隅から右下隅へ向かう斜め取り消し線の非表示または表示状態を指定します。
type: docs
weight: 209
url: /ja/aspose.slides.mathtext/imathborderbox/set_strikethroughtoplefttobottomright/
---
## IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool) メソッド


左上から右下への取り消し線 (デフォルトは false)。ボーダーボックスの左上隅から右下隅へ向かう斜め取り消し線の非表示または表示状態を指定します。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool value)=0
```

## 備考


例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughTopLeftToBottomRight(true);
```

## 参照

* クラス [IMathBorderBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)