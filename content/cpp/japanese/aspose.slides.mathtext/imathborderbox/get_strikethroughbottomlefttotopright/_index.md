---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides for C++ API リファレンス
description: 取り消し線の左下から右上への斜め（デフォルトは false）。ボーダーボックスの左下隅から右上隅へ向かう取り消し線の表示または非表示の状態を指定します。
type: docs
weight: 170
url: /ja/aspose.slides.mathtext/imathborderbox/get_strikethroughbottomlefttotopright/
---
## IMathBorderBox::get_StrikethroughBottomLeftToTopRight() メソッド

Strikethrough Bottom-Left to Top-Right (デフォルトは false). ボーダーボックスの左下隅から右上隅へ引かれる取り消し線の斜め線の表示または非表示の状態を指定します。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughBottomLeftToTopRight()=0
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