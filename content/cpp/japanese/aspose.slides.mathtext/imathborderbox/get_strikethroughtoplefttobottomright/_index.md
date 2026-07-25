---
title: get_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides for C++ API リファレンス
description: 左上から右下への取り消し線 (デフォルトは false)。ボーダーボックスの左上隅から右下隅へ向かう斜めの取り消し線の非表示または表示の状態を指定します。
type: docs
weight: 196
url: /ja/aspose.slides.mathtext/imathborderbox/get_strikethroughtoplefttobottomright/
---
## IMathBorderBox::get_StrikethroughTopLeftToBottomRight() メソッド


Strikethrough Top-Left to Bottom-Right（デフォルトは false）。ボーダーボックスの左上隅から右下隅へ向かう斜めの取り消し線の非表示または表示の状態を指定します。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughTopLeftToBottomRight()=0
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