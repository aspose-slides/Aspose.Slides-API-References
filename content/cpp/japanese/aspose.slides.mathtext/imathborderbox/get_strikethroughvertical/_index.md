---
title: get_StrikethroughVertical()
second_title: Aspose.Slides for C++ API リファレンス
description: Strikethrough Vertical (default is false) - 縦取り消し線の表示または非表示の状態を指定します。
type: docs
weight: 144
url: /ja/aspose.slides.mathtext/imathborderbox/get_strikethroughvertical/
---
## IMathBorderBox::get_StrikethroughVertical() メソッド

Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughVertical()=0
```

## 備考

例:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughVertical(true);
```

## 参照

* クラス [IMathBorderBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)