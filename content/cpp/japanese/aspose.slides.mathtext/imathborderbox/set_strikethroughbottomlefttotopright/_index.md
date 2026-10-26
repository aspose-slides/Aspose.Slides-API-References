---
title: set_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides for C++ API リファレンス
description: 左下から右上への取り消し線（デフォルトは false）。ボーダーボックスの左下隅から右上隅へ向かう斜めの取り消し線の非表示または表示状態を指定します。
type: docs
weight: 183
url: /ja/aspose.slides.mathtext/imathborderbox/set_strikethroughbottomlefttotopright/
---
## IMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool) メソッド

左下から右上への取り消し線 (デフォルトは false)。ボーダーボックスの左下隅から右上隅へ向かう取り消し線の非表示または表示状態を指定します。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool value)=0
```

## 備考

例:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## 参照

* クラス [IMathBorderBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)