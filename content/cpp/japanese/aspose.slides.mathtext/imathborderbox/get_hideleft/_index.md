---
title: get_HideLeft()
second_title: Aspose.Slides for C++ API リファレンス
description: 左側エッジを非表示にするかどうか (デフォルトは false) - ボーダーボックスの左側エッジの非表示または表示状態を指定します。
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/imathborderbox/get_hideleft/
---
## IMathBorderBox::get_HideLeft() メソッド

左側のエッジを非表示にするかどうか (デフォルトは false) - ボーダーボックスの左側エッジの非表示または表示状態を指定します。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideLeft()=0
```

## 備考

例:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideLeft(true);
```

## 参照

* クラス [IMathBorderBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)